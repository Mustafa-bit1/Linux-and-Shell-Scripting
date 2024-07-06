# Linux-and-Shell-scripting


# Introduction to Linux:

Linux is a Unix-like computer operating system assembled under the model of free and open
source software development and distribution. The defining component of Linux is the Linux
kernel, an operating system kernel first released 5 October 1991 by Linus Torvalds.
## (At END find 150 most usefull Linux Commands)
Linux was originally developed as a free operating system for Intel x86-based personal
computers. It has since been ported to more computer hardware platforms than any other
operating system. It is a leading operating system on servers and other big iron systems such as
mainframe computers and supercomputers more than 90% of today's 500 fastest
supercomputers run some variant of Linux, including the 10 fastest.

Linux also runs on embedded systems (devices where the operating system is typically built into the firmware and
highly tailored to the system) such as mobile phones, tablet computers, network routers,
televisions and video game consoles; the Android system in wide use on mobile devices is
built on the Linux kernel.




## Different Desktop OS Market share 2024 

Windows -      74%

OS X (Mac OS)-  15%

Linux  -         6.3%

Others -       4.7%


![pie](https://github.com/Mustafa-bit1/Linux-and-Shell-Scripting/assets/172354785/a37b8334-f48e-4711-b0fe-09bf6844c501)


Reference - https://gs.statcounter.com/os-market-share/desktop/worldwide



## Basic Features of Linux OS


Following are some of the important features of Linux Operating System.

 Portable - Portability means softwares can works on different types of hardwares in
same way. Linux kernel and application programs supports their installation on any kind
of hardware platform.

 Open Source - Linux source code is freely available and it is community based
development project. Multiple teams works in collaboration to enhance the capability
of Linux operating system and it is continuously evolving.

 Multi-User - Linux is a multiuser system means multiple users can access
system resources like memory/ ram/ application programs at same time.

 Multiprogramming - Linux is a multiprogramming system means multiple
applications can run at same time.

 Hierarchical File System - Linux provides a standard file structure in which system
files/ user files are arranged. 

 Shell - Linux provides a special interpreter program which can be used to execute
commands of the operating system. It can be used to do various types of operations, call
application programs etc.

 Security - Linux provides user security using authentication features like password
protection/ controlled access to specific files/ encryption of data.

### Linux Advantages

#### 1. Low cost: 
You don’t need to spend time and money to obtain licenses since Linux and much
of its software come with the GNU General Public License. You can start to workimmediately
without worrying that your software may stop working anytime because thefree trial version
expires. Additionally, there are large repositories from which you canfreely download high
quality software for almost any task you can think of.

#### 2. Stability: 
Linux doesn’t need to be rebooted periodically to maintain performance levels.
Itdoesn’t freeze up or slow down over time due to memory leaks and such. Continuous uptimes of hundreds of days (up to a year or more) are not uncommon.
#### 3. Performance: 
Linux provides persistent high performance on workstations and
onnetworks. It can handle unusually large numbers of users simultaneously, and can make
oldcomputers sufficiently responsive to be useful again.
#### 4. Network friendliness: 
Linux was developed by a group of programmers over the
Internet and has therefore strong support for network functionality; client and server
systems can be easily set up on any computer running Linux. It can perform tasks such as
network backups faster and more reliably than alternative systems.
#### 5. Flexibility:
 Linux can be used for high performance server applications, desktop
applications, and embedded systems. You can save disk space by only installing the
components needed for a particular use. You can restrict the use of specific computers by
installing for example only selected office applications instead of the whole suite.
#### 6. Compatibility:
 It runs all common Unix software packages and can process all common file formats.
#### 7. Choice: 
The large number of Linux distributions gives you a choice. Each distribution is
developed and supported by a different organization. You can pick the one you like best; the core functionalities are the same; most software runs on most distributions.
#### 8. Fast and easy installation: 
Most Linux distributions come with user-friendly installation
and setup programs. Popular Linux distributions come with tools that make installation of
additional software very user friendly as well.
#### 9. Full use of hard disk:
 Linux continues work well even when the hard disk is almost full.
#### 10.Multitasking:
 Linux is designed to do many things at the same time; e.g., a large printing
job in the background won’t slow down your other work.
#### 11. Security:
 Linux is one of the most secure operating systems. “Walls” and flexible file
access permission systems prevent access by unwanted visitors or viruses. Linux users have
to option to select and safely download software, free of charge, from online repositories
containing thousands of high quality packages. No purchase transactions requiring credit card
numbers or other sensitive personal information are necessary.
#### 12. Open Source:
 If you develop software that requires knowledge or modification of the
operating system code, Linux’s source code is at your fingertips. Most Linux applications
are Open Source as well.

### Linux Distributions

Linux has various distributions each with different functionalities.
Some popular ones are 

-> Fedora 

-> Ubuntu 

-> Kali Linux 

-> Redhat 

-> CentOS 

-> Elementary OS 

-> Linuxmint 

-> Manjaro.


![most-popular-linux-distro](https://github.com/Mustafa-bit1/Linux-and-Shell-Scripting/assets/172354785/dc924da8-f7d8-4835-a98c-98c6daec0c3f)

### My Linux os - Ubuntu
![ubu](https://github.com/Mustafa-bit1/Linux-and-Shell-Scripting/assets/172354785/137ef0ce-1f23-4533-8d28-665d6592af6c)
### Architecture


![linux archi](https://github.com/Mustafa-bit1/Linux-and-Shell-Scripting/assets/172354785/3e734eb0-d8fa-4450-b4f5-d9a17c391450)


# Some most useful commands in linux


![top-50-linux-commands](https://github.com/Mustafa-bit1/Linux-and-Shell-Scripting/assets/172354785/71acb22c-a005-4d7b-ba52-5affaf05ba33)



### File and Directory Management

ls - List directory contents

cd - Change the directory

pwd - Print working directory

mkdir - Make directories

rmdir - Remove empty directories

touch - Change file timestamps or create empty files

cp - Copy files and directories

mv - Move or rename files and directories

rm - Remove files or directories

find - Search for files in a directory hierarchy

locate - Find files by name

du - Estimate file space usage

df - Report file system disk space usage

tar - Archive files

zip - Package and compress files

unzip - Extract compressed files

chmod - Change file modes or Access Control Lists

chown - Change file owner and group

ln - Make links between files

stat - Display file or file system status

### Text Processing

cat - Concatenate and display files

more - View file contents interactively

less - View file contents interactively with backward navigation

head - Output the first part of files

tail - Output the last part of files

grep - Print lines matching a pattern

awk - Pattern scanning and processing language

sed - Stream editor for filtering and transforming text

cut - Remove sections from each line of files

sort - Sort lines of text files

uniq - Report or omit repeated lines

tr - Translate or delete characters

wc - Print newline, word, and byte counts for each file

diff - Compare files line by line

cmp - Compare two files byte by byte

### Process Management
ps - Report a snapshot of current processes

top - Display Linux tasks

htop - Interactive process viewer

kill - Send a signal to a process

killall - Kill processes by name

pkill - Look up or signal processes based on name and other attributes

bg - Resume a suspended job in the background

fg - Bring a job to the foreground

jobs - List active jobs

nice - Run a program with modified scheduling priority

renice - Alter priority of running processes

### Networking
ping - Send ICMP ECHO_REQUEST to network hosts

ifconfig - Configure a network interface

ip - Show/manipulate routing, devices, policy routing, and tunnels

netstat - Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships

ss - Another utility to investigate sockets

traceroute - Print the route packets take to a network 

curl - Transfer data from or to a server

wget - Retrieve files from the web

scp - Secure copy (remote file copy program)

rsync - Remote file and directory synchronization

ssh - OpenSSH SSH client (remote login program)

telnet - User interface to the TELNET protocol

ftp - Internet file transfer program

nmap - Network exploration tool and security/port scanner

dig - DNS lookup

host - DNS lookup utility

### System Monitoring and Performance

uptime - Tell how long the system has been running

dmesg - Print or control the kernel ring buffer

free - Display amount of free and used memory in the system

vmstat - Report virtual memory statistics

iostat - Report CPU and input/output statistics for devices and partitions

iotop - Display I/O usage by processes or threads

sar - Collect, report, or save system activity information

mpstat - Report CPU statistics

lsof - List open files

strace - Trace system calls and signals

time - Measure the time taken by program execution

### User Management
who - Show who is logged on

w - Show who is logged on and what they are doing

whoami - Print the effective user ID

id - Print user and group information

useradd - Create a new user or update default new user information

usermod - Modify a user account

userdel - Delete a user account and related files

passwd - Update a user's authentication tokens

groupadd - Create a new group

groupmod - Modify a group

groupdel - Delete a group

### Disk and File System Management
mount - Mount a file system

umount - Unmount file systems

fdisk - Manipulate disk partition table

mkfs - Build a Linux file system

fsck - File system consistency check and repair

tune2fs - Adjust tunable file system parameters on ext2/ext3/ext4 file systems

blkid - Locate/print block device attributes

parted - A partition manipulation program

lsblk - List information about block devices


### Package Management (varies by distribution)

apt-get - APT package handling utility (Debian-based)

yum - Package manager for RPM-based distributions

dnf - Next-generation version of yum (Fedora)

rpm - RPM package manager

dpkg - Debian package manager

snap - Package management system

#### Debian-based Systems

apt - Advanced Package Tool, more user-friendly interface for APT (replaces apt-get and apt-cache)

apt-cache - Query the APT cache

aptitude - Terminal-based interface to APT

#### RPM-based Systems

zypper - Command-line interface of ZYpp package manager (openSUSE and SLES)

dnf-automatic - A DNF module for automatic updates

dnf-plugins-core - Core plugins for DNF package manager

#### Arch-based Systems

pacman - Package manager utility (Arch Linux)

yay - Yet Another Yaourt, AUR helper written in Go (Arch User Repository)

yaourt - AUR helper (no longer maintained, replaced by yay and other AUR helpers)

#### Red Hat-based Systems

rpm-ostree - Hybrid image/package system (Fedora Silverblue, CoreOS)

subscription-manager - Manage Red Hat subscriptions and entitlements

### Universal Package Management
flatpak - System for building, distributing, and running sandboxed desktop applications on Linux

appimage - Universal software packaging format

conda - Package, dependency, and environment management for any language (commonly used in data science)

### General System and Network Management
ssh - Secure Shell for remote server access

scp - Secure copy for transferring files between hosts

rsync - Remote file synchronization

curl - Command-line tool for transferring data with URLs

wget - Network downloader

ping - Check connectivity to a host

traceroute - Track the route packets take to a host

ifconfig / ip - Network interface configuration and management

netstat / ss - Network statistics and socket status

nmap - Network exploration and security auditing tool

### Cloud-Specific Tools and CLI
aws - AWS Command Line Interface for managing Amazon Web Services

gcloud - Google Cloud Platform Command Line Interface

az - Microsoft Azure Command Line Interface

openstack - Command Line Interface for managing OpenStack services

kubectl - Kubernetes Command Line Interface for managing Kubernetes clusters

terraform - Infrastructure as Code (IaC) tool for building, changing, and versioning infrastructure

ansible - Automation tool for configuration management and application deployment

packer - Create identical machine images for multiple platforms from a single source configuration

### Container Management
docker - Command Line Interface for managing Docker containers

docker-compose - Define and run multi-container Docker applications

podman - Manage containers and pods without requiring a daemon

crictl - Command-line interface for CRI-compatible container runtimes

### Monitoring and Logging
top / htop - Display Linux tasks and system performance

vmstat - Report virtual memory statistics

iostat - Report CPU and I/O statistics

dmesg - Print kernel ring buffer messages

journalctl - Query and display messages from the systemd journal

logrotate - Rotate, compress, and mail system logs

cloudwatch - AWS CloudWatch CLI for monitoring AWS resources

prometheus - Open-source monitoring system and time series database

grafana-cli - Command Line Interface for managing Grafana

### Security and Access Management
ufw - Uncomplicated Firewall, frontend for managing firewall rules

iptables - Administering IP packet filter rules

fail2ban - Ban IPs with too many failed login attempts

auditd - User space component to collect audit records

selinux - Manage SELinux policies and contexts


# Shell Scripting
Shell scripting is the practice of writing scripts, or sequences of commands, to be executed by the shell, a command-line interpreter in Unix-like operating systems such as Linux and macOS. Shell scripts automate repetitive tasks, manage system operations, and streamline complex workflows.

Key Components of Shell Scripting
Shell: The shell is a command-line interface (CLI) that provides a user interface for accessing the operating system's services. Common shells include Bash (Bourne Again Shell), Zsh (Z Shell), and Ksh (Korn Shell).

Script: A shell script is a file containing a series of commands that the shell can execute. These scripts are used to automate tasks that would otherwise be performed interactively at the command line.

### Shell is broadly classified into two categories –

Command Line Shell

1. Command Line Shell
2. Graphical shell

#### Command Line Shell
Shell can be accessed by users using a command line interface. A special program called Terminal in Linux/macOS, or Command Prompt in Windows OS is provided to type in the human-readable commands such as “cat”, “ls” etc. and then it is being executed. The result is then displayed on the terminal to the user. A terminal in Ubuntu 16.4 system looks like this –


![ubu](https://github.com/Mustafa-bit1/Linux-and-Shell-Scripting/assets/172354785/13ae30bc-0035-45ad-9bd7-bb4eb7fd2c16)

Command Line Shell allows users to store commands in a file and execute them together. This way any repetitive task can be easily automated. These files are usually called batch files in Windows and Shell Scripts in Linux/macOS systems.

#### Graphical Shells
Graphical shells provide means for manipulating programs based on the graphical user interface (GUI), by allowing for operations such as opening, closing, moving, and resizing windows, as well as switching focus between windows. Window OS or Ubuntu OS can be considered as a good example which provides GUI to the user for interacting with the program. Users do not need to type in commands for every action. A typical GUI in the Ubuntu system –

![GUI-shell](https://github.com/Mustafa-bit1/Linux-and-Shell-Scripting/assets/172354785/69db17d7-b654-4d9f-9a33-d6e8f675d133)

#### Why do we need shell scripts?
There are many reasons to write shell scripts:

> To avoid repetitive work and automation

> System admins use shell scripting for routine backups.

> System monitoring

> Adding new functionality to the shell etc.

#### Some Advantages of shell scripts
> The command and syntax are exactly the same as those directly entered in the command line, so programmers do not need to switch to entirely different syntax

> Writing shell scripts are much quicker

> Quick start

> Interactive debugging etc.

#### Some Disadvantages of shell scripts
> Prone to costly errors, a single mistake can change the command which might be harmful.

> Slow execution speed

> Design flaws within the language syntax or implementation

> Not well suited for large and complex task

> Provide minimal data structure unlike other scripting languages. etc.

#### Reference GeeksforGeeks https://www.geeksforgeeks.org/introduction-linux-shell-shell-scripting/amp/

### Steps to run a script 
1. Create a New File : Use a text editor to create a new file. You can use editors like nano, vim, or gedit, or create the file directly from the command line.

```bash
  vi myscript.sh
```
2. Add the Shebang : The first line of the script should be the shebang (#!), which specifies the interpreter that will execute the script. For a Bash script, it would look like this:

```bash
  #!/bin/bash
```

3. Write Your Script : Add the commands you want to be executed.
   
```bash
  #!/bin/bash

  name=Mustafa
  city=Bangalore

  echo "Hello $name Welcome to $city"
```
4. Save and Close the File
5.  Make the Script Executable and run The Script: Change the file permissions to make the script executable. Use the chmod command and run using ./myscript.sh

```bash
  chmod +x myscript.sh   // Permisions to execute
  ./myscript.sh         // Run

```
### Output
```bash
  Hello Mustafa Welcome to Bangalore

```
    
   
