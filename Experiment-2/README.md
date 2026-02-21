# Experiment: Basic Linux Commands, Run Levels, and Help Utilities

## Aim
To explore and practice basic Linux commands, understand system run levels (targets), and use Linux help utilities.

## Objective
* To learn basic Linux command-line operations.
* To understand system run levels (systemd targets).
* To use help utilities like `man` and `--help`.
* To improve efficiency using auto-completion.

## Theory

### Linux Command Line Interface (CLI)
The Linux CLI allows interaction with the operating system using commands. It provides faster and more powerful control compared to graphical interfaces, especially for system administration and automation tasks.



## Step-by-step Procedure

1. **First, logged into the Linux virtual machine.**
2. **Then, opened the Terminal.**
3. **After that, executed basic system commands:**
   ```bash
   pwd
   ls
   whoami
   date
   uptime
   ```

4. **Then, navigated directories using:**
   ```bash
   cd /home
   cd ~
   ```

5. **After that, used manual pages to understand commands:**
   ```bash
   man ls
   man cd
   ```

6. **Then, exited the manual page using the <kbd>q</kbd> key.**

7. **After that, used help options:**
   ```bash
   ls --help
   systemctl --help
   ```

8. **Then, checked system run level / target:**
   ```bash
   runlevel
   systemctl get-default
   ```

9. **After that, switched system targets:**
   ```bash
   systemctl isolate multi-user.target
   systemctl isolate graphical.target
   ```

10. **Then, used classic runlevel commands:**
    ```bash
    sudo init 3
    sudo init 5
    ```

11. **After that, practiced auto-completion using the <kbd>Tab</kbd> key.**

12. **Finally, cleared the terminal screen:**
    ```bash
    clear
    ```

## Configuration Commands
The following commands were utilized during this experiment:
```bash
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
```

## Results
* Basic Linux commands executed successfully.
* Manual pages and help options displayed correctly.
* System run level / target identified.
* Commands executed efficiently using auto-completion.
