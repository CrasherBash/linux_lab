**Experiment Title**

To explore and practice basic Linux commands, understand system run levels (targets), and use Linux help utilities.

**Objective**

To learn basic Linux command-line operations

To understand system run levels (systemd targets)

To use help utilities like man and --help

To improve efficiency using auto-completion

**Theory**
Linux Command Line Interface (CLI)

The Linux CLI allows interaction with the operating system using commands. It provides faster and more powerful control compared to graphical interfaces, especially for system administration and automation tasks.

**Step-by-step Procedure**

Step 1: First, logged into the Linux virtual machine.

Step 2: Then, opened the Terminal.

Step 3: After that, executed basic system commands:

pwd

ls

whoami

date

uptime

Step 4: Then, navigated directories using:

cd /home

cd ~

Step 5: After that, used manual pages to understand commands:

man ls

man cd

Step 6: Then, exited the manual page using the q key.

Step 7: After that, used help options:

ls --help

systemctl --help

Step 8: Then, checked system run level / target:

runlevel

systemctl get-default

Step 9: After that, switched system targets:

systemctl isolate multi-user.target

systemctl isolate graphical.target

Step 10: Then, used classic runlevel commands:

sudo init 3

sudo init 5

Step 11: After that, practiced auto-completion using the Tab key.

Step 12: Finally, cleared the terminal screen:

clear
**Configuration Commands**
pwd

ls

cd

whoami

date

uptime

man

systemctl

runlevel

clear

**Results**

Basic Linux commands executed successfully

Manual pages and help options displayed correctly

System run level / target identified

Commands executed efficiently using auto-completion

