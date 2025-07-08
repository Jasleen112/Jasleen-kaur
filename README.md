
25/06/2025
 
My first day in training is very valuable to me.Our first topic is about linux.
Linux is a operating system which is completely different from windows.
DIFFERENCE BETWEEN LINUX AND WINDOWS:
   1.Linux is a open source system i.e anybody can download it whereas windows is not a open source system.
   2.Linux is free of cost while windows requires licensing which varies by designing and usage.
   3.In linux,there is no money required  whereas windows requires purchases.
 HOW TO DOWNLOAD LINUX:
 1.Firstly we need a virtual box in which we can add linux.
 2.We need a ISO file.
 3.We need to download microsoft visual C++.
CARRER OPPORTUNITIES:
  I explore more about my career that what is have to do after my degree or in my degree.My dream is that I work in cyber security companies.So that's it from my 1st day of training
BOOTING:It is the process of stating a computer.It is of two types:
1.COLD/HARD BOOT:Starting the computer from power off state.Ex.Mac,Linux
2.WARM/SOFT BOOT:Restarting the computer without power off.ex.windows.


26/06/2025


So our next topic is Kernel and shell.
WHAT IS KERNEL?
 It is the core of computer that is responsible for working of the computer.
WHAT IS SHELL?
 It acts as a interface between user and operating system.
TYPES OF SHELL: 1.BASH:most common shell
                2.SH:original shell
                3.ZSH:more features 
                4.FISH:modern,interactive
CATEGORIES OF SHELL: 1.Command line shell
                     2.Graphical shell

       FILE SYSTEM STRUCTUTRE:
       
     DIRECTORY                              FUNCTION
   
     /root:                   The top level directory from which all other directories work.
     
     /bin:                   Contains executable files.
   
     /boot:                  Stores files needed for booting the system including kernel.

     /dev:                   Contain device files that represents hardware devices.

     /home:                   Personal directories from user.

     /lib:                    Contain library files.
     
     /media:                  Mount point for removable media like USB drives.

     /mnt:                    Temporary Mount point for file systems.
 
     /opt:                    Contain optional apps.
   
     /srv:                    Contains data for services provided by system.

     /tmp:                    Store temporary files.

     /usr:                    Contains user related programs, libraries and documents.
 
     /var:                    Stores variable data like log files,user tracking.

   COMMANDS:
   
    commands.                description           
 
    ls.                   list the contents
 
    date.                 show the current date and time.

    whoami.               Display current user name.
 
    cd.                   change directory.

    mkdir.                make a new directory.

    cat.                  Create list with contents.

    touch.                Create file with contents.

    cp.                   copy the files 

    pwd.                  print the current working directory.

    whereis.              show location of binary,source 

    whatis.               To get information about command.


SYNTAX OF COMMANDS:
 
1.ls(optional)
2.date
3.whoami
4.cd[directory]
5.mkdir directory_name
6.cat>filename
7.touch filename
8.cp[source]
9.pwd
10.whereis[command]
11.whatis[command]

 27/06/2025

 DUAL BOOTING: in this two operating system can be used in one computer.we have to choose which system to use.
 
 BARE METAL INSTALLATION:Installing an operating system directly on physical computer,not inside VMware.The operating system can be installed using pen drive.
 
 META INSTALLING:Installing a package that installs many other related packages.we install one thing,it brings bunch of things with it.
 
 PARTIONING SCHEME:Dividing hard disk into sections so that each part can be used for different purpose.Linux uses multiple partitions to keep the system organised,secure and flexible.
 1.MBR(Master Boot Record):maximum 4 primary partitions.Support upto 2TB.it has less flexibility.
 2.GPT(Guid Partition Table):It supports upto 128 partitions.It supports disks larger than 2TB.It is more flexible.

 FILE AND DIRECTORY PERMISSIONS:It is the backbone of linux security ensuring that authorized user can interact.
 
 TYPES OF COMMANDS:
 1.chmod(change mode):

                  a.It is used to change the permissions like read,write,execute.
                    Syntax- chmod[permission] [filename]
                  b.  chmod +x filename.sh
                          x enables files to execute.
                  c.  chmod 444 filename.sh 
                         Give permission to read files.
                  d.  chmod 644 filename.sh 
                        It enables permissions only to owner 2.
2.chown(change owner):

                  Syntax:group file.txt
           change owner to user change the group to group so that other users in that group can access the file.

REDIRECTION:Redirection means sending the output or input of a command to somewhere else.

                      Redirection operators

       Type                 Symbol                  Example              
      Output                  >                    echo "Hello" > file.txt
      Append                  >>                   echo "World" >> file.txt
      Input                   <                      wc -l < file.txt

 PIPE IN LINUX

 PIPE:Take the output of one command and pass it to other command.
        Syntax
      command1|command 2
      command 1-generates output 
      command 2-takes that output as input

SHELL PROGRAMS:

1.Use of variables:

2.Multiplication table of any number:

3.Compare two variable:

30/6/2025

FILE COMPRESSION:File compression in linux,helping to reduce the sizes of files.

USE OF FILE COMPRESSION: 
Save storage space:Compressed file take up less disk space,allowing you to store more data.
Faster transmission:Smaller files transfer more quickly over networks.

There are several commands available for compressing files:
1.Gzip:uses to compress file.It reduce the size of the file.It compress the filename and replace it with filename.gz.
  Syntax - gzip filename 
example-gzip notes.txt creates notes.txt.gz and delets notes.txt

This command will compress notes.txt and creates new file named notes.txt.gz,replacing the original file.
DECOMPRESS A FILE:to decompress the files we can use gunzip command.

 gunzip  notes.txt.gz
This will decompress the file and remove the .gz extension,restoring the original notes.txt file.

WILDCARD COMMANDS-Matches file without full names.

    Symbol                     Meaning 
     *                       matches zero or more character 
     ?                       matches exactly one character 
     [abc]                   matches one character from set
     [a-z]                   matches any character in range

 ESCAPING CHARACTERS:Means using a special symbol before a character to tell the computer to treat that character literally,not as special or reserved symbol.

       character to escape                       How to escape                               Meaning 

       space()                             Using backslash\ or quotes                    to treat space as a part of filename or command argument.
       Backslash(\)                        Use double backslash \\                       to represent a literal backslash.
       Dollar sign($)                      Use backslash  \$                             to prevent variable expansion.
       Asterisk(*)                         Use backslash  \*                             to treat * literally,not as a wildcard.
       Question Mark(?)                    Use backslash/?                               to treat ? literally ,not as a single character wildcard. 
       Quotes(" or ')                      Use backslash\" or \'                         to include quotes in strings.
       Brackets([])                        Use backslash\[ and \]                        to treat brackets literally.

  QUOTES:

             QuoteType                          Syntax                                         Description

          Single quotes                         'text'                                    Preserves literal value of all characters inside.
          Double quotes                         "text"                                    Preserves most character literally,but allows variable expansion and command substitution.
          Backslash                             \char                                     Escapes the next character to be treated literally


HARDWARE:Computer hardware refers to the physical components of a computer that you can see and touch.These components work together to process input and deliver output based on user 
         instructions.In this article,we'll explore the different types of computer hardware,their functions and how they interact to make your computer work.

The computer has mainly has two major components:

                 HARDWARE TYPE                           DESCRIPTION 

         Input Devices                           Devices allows user to interact with computer by entering data or commands.
                                                 These devices convert the input into a format that the computer can process.

         Output Devices                          Output devices display the result of tasks given to the computer in a human-readable form.

         Storage Devices                         Some devices are used for storage purposes and are known as secondary storage devices.

         Processing Unit                         Components that process data and execute instructions.

         Memory                                  Temporary storage used by the CPU to hold data and instructions.

         Motherboard                             It is the main circuit board inside the computer and it contains most of the electronic components 
                                                 together.All the components of the computer are directly or indirectly connected to the motherboard.

         Power Supply                            All of a computer system's parts are powered by power source.

         Networking Hardware                     Devices that connect computers and enables communication.


MOTHERBOARD:A motherboard is the main circuit board of a computer.It is the central platform that connects and allows communication between all the different parts of a computer.

               Components                                     Description 

         CPU Socket                                     The slot where the processor is installed.
         RAM Slots(DIMM)                                Slots for installing memory modules(RAM)
         Chipset                                        Manages data flow between CPU,memory and peripherals.
         BIOS/UEFI Chip                                 Firmware that initialize hardware during boot-up
         Power Connectors                               Connectors for power supply to distribute electricity to components.
         Expansion Slots                                Slots (PCI,PCIe) for adding graphics cards,network cards etc.
         SATA Ports                                     Connectors for storage devices like HDDs and SSDs.
         M.2 Slots                                      Connectors for modern-high speed SSDs.
         CMOS Battery                                   Powers the BIOS memory to retain settings when the PC is off
         USB Headers                                    connectors for USB ports on the front or back panel
         Audio connectors                               Ports for audio input/output devices
         Network Ports(Ethernet)                        Connectors for wired network connection


1/07/2025

GPU(GRAPHICS PROCESSING UNIT):GPU stands for Graphics Processing Unit.It is a specialized electronic circuit designed to rapidly process and manipulate images and graphics.Today GPUs                                  are also used for many other computing tasks beyond graphics,including artificial intelligence and scientific computing.

TYPES OF GPUs: 1.INTEGRATED GPU:It is built in the CPU.It is less powerful.e.g.Intel UHD.
               2.DEDICATED GPU:It is a separate hardware.It is very powerful,ideal for gaming and heavy tasks.
USES:Video games,video editing,artificial intelligence,scientific simulations.

PCU(PERSONAL COMPUTER UNIT):INSTALLATION AND HARD DISK PREPARATION:
PARTITIONING:The first step of partitioning is to organize the hard disk into Primary(C:Drive).
             Avoid storing personal/important files in C-Drive.

WHY C-DRIVE IS NOT RECOMENDED TO STORE IMPORTANT FILES?
Because in case if windows crashes,files in D,E,F-Drive are safer and can often be recovered.If we put files in same drive then there will be Data lose if windows get crashed.

OPTIMISATION:Optimisation means making something as good,efficient or effective as possible.In computer world,ir refers to speeding up software or hardware so it runs faster or uses                  fewer resources improving algorithms to solve problems more efficiently.

DEFRAGMENTATION:It is the process of reorganizing fragmented data on a hard disk so that related pieces are stored close together.This improves files access speed and overall system                     performance on traditional HDDs.It's not nedded for SSDs,which use a different methods called TRIM.

DRIVERS:Drivers are software that let the operating system communicate with hardware like printers,keyboards or graphic cards.Without them,hardware won't work properly.
ISSUES FACED WHILE USING PRINTER: 1.Printer not printing:Cause - connectivity issues or outdated drivers.
                                                         Solution - Check cables/wifi,restart printer and PC,reinstall or update drivers.
                                  2.Paper jams:Cause - Misaligned or poor-quality paper.
                                               Solution - Gently remove jammed paper,align guide,use recommended paper type.
                                  3.Slow printing:Cause - High-resolution settings or complex documents.
                                                  Solution - lower printing quality settings,use draft mode for basic prinnts.
                                  4.Poor print quality:Cause - Dirty print heads or low.
                                                       Solution - Run print head cleaning utility,check ink levels.
                                  5.Printer offline:Cause - Network or driver issues.
                                                    Solution - Reconnect to network,set printer as default,restart spooler service

BSOD(BLUE SCREEN OF DEATH):It is an error screen displayed by the Windows Operating System when the system encounters a critical error that it cannot recover from,causing the system to                             crash.

WHAT CAUSES A BSOD?
 1.Hardware failures - such as faulty Ram,hard drives or overheating.
 2.Driver issues - incompatible or corrupt device drivers.
 3.Corrupt system files - essential files missing or damaged.
 4.Overclocking - pushing hardware beyond its rated limit.
 5.Software bugs - Buggy updates or malicious software.
 6.Power supply issues - sudden shutdown or unstable power.

WHAT HAPPENS DURING A BSOD?
:The screen turns blue.
:An error message is shown(e.g.CRITICAL_PROCEED_DIED)
:A stop code is displayed (helps in diagnosing the error).
:Sometimes, a QR code or file name is included.

HOW TO FIX BSOD?
1.Restart the computer - sometimes it's just a one-time issue.
2.Update drivers - Use device Manager or Windows Update.
3.Check Hardware - Run memory tests or disk checks.
4.Scan for viruses/malware.
5.Uninstall recent updates or apps - Especially if the BSOD started afterward.
6.Use system restore - Roll back to a stable point.

 
