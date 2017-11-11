# cooperative-shutdown

To perform  shutdown
$shutdown

To perform reboot
$reboot
or 
$shutdown --reboot

To lock shutdown 
$shutdown --lock


usage: shutdown [-h] [-u USER] [-l] [-r] [-x] [-i] [--setup]

Co-operative shutdown between multiple users

optional arguments:
  -h, --help            show this help message and exit
  -u USER, --user USER  user, by default, current linux user name is used
  -l, --lock            lock to disable others from shutting down system
  -r, --release         only release lock, do not perform shutdown.
  -x, --reboot          reboot the system.
  -i, --info            get current shutdown locks info
  --setup               put entry into /etc/.bashrc to substitute this in
                        place of default shutdown commands
