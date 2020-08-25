BashBSD - Porting BSD to Other OSs (and BSD...wait, this is weird...)

COMMANDS:
reboot - Restart BashBSD
exit Exit to Terminal
vi - Run VI test editor
clear - Clear screen
run - Run custom/Linux/Mac/Unix command
help - Show help
tar - Run TAR Archiver
bootpak - BootPak package manager
ver - Show BashBSD version

DEPENDIENSES:
-bash
-wget
!NOTE! YOU MUST INSTALL THERE DEPENDIENSES,TO GET SYSTEM WORK!

                                        DOWNLOAD:
v4.00-RELEASE: http://github.com/glowiak/BashBSD/raw/master/BashBSD_v4.00.tar.Z

This files are compressed with Z, to extract it type:
uncompress BashBSD_vX.XX.tar.Z
tar -xvf BashBSD_vX.XX.tar

To run it on Window$ use WSL or try BatchBSD http://github.com/glowiak/BatchBSD

Syntax for BootPak:
net - Install Package from internet
local - install local package
uninstall - uninstall package
help - display BootPak help
chrepo - Change BootPak Repo (this will be saved in etc/bootpak/repo.conf)

BootPak GitHub Repo: http://github.com/glowiak/bootpak <-- From this repo You can download packages for offline install :D

##############################################################################################################
BootPak install process look like MAKE from FreeBSD ports :D

Link to List Of Official BashBSD Repos: https://github.com/glowiak/bootpak/releases (all repos have instruction how to install it and packages in repo)

BootPak package format: tar.xz

BootPak package map:
  package.tar.xz         (package folder archived with tar and compressed with xz)
    packagefolder        (contain package files and other package folders, must be created to get working package)
      packagefile1       (there are exaple package files)
      packagefile2
      packagefile3
      packagefile8
      packagefolder1                (there are example package folders)
        packagefolder1file1         (the are example package files in example package folders)
      packagefolder2
      packagefolder3


You can create You own repo with You own software!
You can also create you own packages!

NOTE: To run it don't type './boot.sh', you must type 'bash boot.sh'!
