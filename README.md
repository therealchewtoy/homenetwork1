# homenetwork1
1. Start with a CentOS7 host that will be your physical system.
   1. See the home network diagram for how this should be connected.
   1. Expect to use at least four NICs and two VLANs.
   1. Allocate plenty of disk -- you're going to create a bunch of VMs.
1. Run 'yum update' to update all of the packages.  Keep them updated.
1. Install git with 'yum install git-all'.
1. Install powertop with 'yum install powertop'.
1. Create a user called macbookbackup:
   1. useradd macbookbackup
   1. passwd macbookbackup
1. hostnamectl set-hostname minion
1. yum install rsync
