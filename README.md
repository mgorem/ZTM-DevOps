What to Learn within these five months: November 28, 2025 - March 15, 2026
**I ZTM DevOps - Few Certificates**
1. DevOps Bootcamp: Learn Linux & Become a Linux Sysadmin. Objectives:
    -  Everything you need to become a professional Linux Sysadmin and get hired
    - Master all of the key concepts and commands in Linux starting from scratch
    - Learn how to set up the Linux environment (installing both Ubuntu and CentOS on a virtual machine)
    - Build a complete understanding of Linux OS (Distribution Independent) as a complete beginner
    - For each Linux key concept or command, you'll also get a cheatsheet, quiz, and practice exercises
    - Network Security & Ethical Hacking key concepts (Reconnaissance, Sniffing, Iptables Firewall and more)
    - Understanding of Linux File Permissions, Processes, User Account Management, Linux Networking or Software Management
    - Ability to actually apply a deep understanding of Linux on real-world projects
    - Acquire a solid foundation of Netfilter/Iptables Linux Firewall (Chains, Tables, Matches, Targets)
2. Complete Python Developer in 2026: Zero to Mastery
3. AWS Certified Cloud Practitioner
4. Master the Coding Interview: System Design + Architecture
5. AWS Certified Solutions Architect
6. Bash Scripting: Learn Shell Scripting
7. DevOps Bootcamp: Terraform
8. Advanced Ethical Hacking Bootcamp: Network Hacking & Security
9. The Networking Bootcamp (CompTIA Network+ Certification)
10. Complete SQL + Databases Bootcamp
11. Apply To 5 Jobs You Really Want
12. Complete Node.js Developer: Zero to Mastery
13. Complete Cybersecurity Bootcamp: Zero to Mastery
14. Future Proof Yourself: Goal Setting for Your Career
15. Learning to Learn [Efficient Learning]
16. Read the Principles for Programmers
17. Take Your Next Step - Take Career Path Quiz.

(**II) NOTES**
Objectives (What to learn): **Becoming a Linux SysAdmin, Linux Engineer**

-Environment Setup

-Linux Fundamentals (file systems, Account management, file permissions, process management)

-Networking

-Software Management

-System Administration

-Bash shell scripting

-Docker

-Linux Security

-Web and DNS Servers

-Ansible

-IPFS (Interplanetary File System)

-SSH and Public Key Authentication

- **Linux Distribution/ Distro** - An OS made from a collection of software based on the linux kernel, and often a package management system.
- Linux OS comprises of:
    - Linux Kernel (core of the operating system) - provides an interface between the hardware, software and users.
    - GNU shell utilities, terminal interfaces -
    - Graphical desktop environment.
- Some Os’s OpenWRT- embedded devices like routers, Linux Mint, Pop os, raspberry pi os
- Check on linux distros on [**distrowatch.com](http://distrowatch.com)** especially for the popularity.
- Most popular linux distros: Ubuntu (Free) or Redhat (Commercial - acquired by IBM). You can use AlmaLinux or Rocky Linux which are built on redhat.

- Preference is Ubuntu since it works well as a server and a desktop OS.
- Installing Ubuntu, and setting up everything. (Done)

Terminals, Consoles, Shells and Commands

**Terminal Emulator/Terminal:** A program that opens a window and allows us to write commands. e.g Gnome, console, emulator

- allows us to access a system through a shell.

**Shell/ Command Interpreter**: A program that takes commands from user and gives them to the OS kernel for execution.

- Takes commands from user, checks whether they are syntactically correct.
- Gets started when user logs in a console or starts a terminal.
- In each terminal a shell opens and waits for commands.

Example Shells:

- Bash
- Bourne Shell
- C Shell
- Korn Shell
- Z Shell

**Console**: Special type of terminal that starts if no GUI (Graphical User Interface) was installed.

Linux Commands Structure (Has 100s of commands)

Getting help and man pages (manual pages):

- **‘man ls’** - opens man page. type **‘h’** to get additional help, **‘q’** get out of screen, **‘q’** again to exit man program. ‘g’ get to the beginning of the man page e.t.c google the rest when needed.
- You can also use: **‘help cd’** to find help or **ls - - help**
- **‘ifocnfig’** - Used to display info about network interfaces and configure them. Used after installing net tools package i.e **‘sudo apt install net-tools’**
- How to **search for a command, feature or keyword** in all man pages **‘man -k ifconfig’** or **‘man -k copy files’**
- To find out what does the option -a of the ls command do: **open man page of ls (’man ls’) and write ‘\-a’**

TAB Key

- Used to complete the command automatically e.g **‘if’** is completed to **‘ifconfig’**
- Press **tab twice** for it to display all the files with a specific name
- Avoid white spaces and instead use tab completion.

BASH shortcuts every Linux admin uses

- **‘ctrl l’** or **‘clear’** - clears screen
- **‘ctrl d’** or **‘exit’** - closes the bash shell
- **‘ctrl a’** - moves cursor to the beginning of the line
- **‘ctrl e’** - moves cursor to the end of the line
- **‘ctrl u’** instead of backspace multiple times - deletes all x-ters  before the cursor by cutting and adding them to the clip board
- **‘ctrl c’** - interrupt the long process going on in a terminal

The Bash History

- **‘.bash_history’** is the file that stores history of the commands a user used in his file.
- commands stored in this file is controlled by ‘HISTFILESIZE’ i.e **‘echo HISTFILESIZE’**
- **‘echo HISTSIZE’** - ****controls how many commands from your bash history will  be stored in the memory
- **‘!17’ or from the bottom, ‘! -3’**- Helps to run a command from history
- **‘!!’** - to run the previous command
- ‘! command name: first letter’ - to find the command
- **‘CTRL + R’** and start typing command - helps us find a previously used command (exit using control + G)
- removing commands from history - **‘history -d ‘line number’**’
- **‘history -c**’ - removes entire history

Running Commands Without Living a Trace

- Leave a space before a command and the command will not appear in the history.
- ‘HISTCONTROL’ - Avoids saving commands in history - to set it up, type: ‘echo HISTCONTROL’, then HISTCONTROL=ignoreboth

Recording Date and Time for each line

- To display timestamp in history file, set **‘HISTIMEFORMAT=%d/%m/%y %T’**
- **‘HISTIMEFORMAT=%d/%m/%y %T’ >> .bashrc** - adding it to .bashrc file for it to be persistent after logging out.

**root (super user or admin) vs non-privileged users**

Different ways to gain super user rights in linux:

- **‘sudo su’** - superuser do substitute user - sudo(ubuntu), wheel(CentOS)
- Creating a new group as admin - **‘sudo groupadd myadmin’**
- Create new user - **‘sudo useradd john’**
- **‘sudo passwd root’** - used to change a password
- **‘passwd student’** - changing user password in CentOS
- **‘sudo - k’** - It invalidates your current sudo credentials, such that you have to enter your password again.
-

(**II) PNPT - TCM Security**
(**III) Google Cybersecurity Cetificate**