# **Linux Basics:**

1.  **Navigating the File System:**
    - `ls`, `cd`, `pwd`, `cp`, `mv`, `rm`, `mkdir`, `rmdir`
2.  **File Permissions and Ownership:**
    - `chmod`, `chown`, and understanding `rwx` permissions.
3.  **Basic File Operations:**
    - Viewing and editing files with `cat`, `less`, `more`, `nano`, or `vim`.
4.  **Process Management:**
    - `ps`, `top`, `kill`, and basic use of `systemctl` or `service` commands.
5.  **Package Management:**
    - Installing, updating, and removing packages (`apt`, `yum`).
6.  **Basic Networking:**
    - Understanding IP addresses, `ping`, `ifconfig`/`ip`, and `netstat`.
7.  **User Management:**
    - Adding and removing users, groups, and basic authentication.

# **Linux Tasks:**

1.  **Task 1: File System Navigation**
    
    - Create a new directory called `practice` in the home directory.
    - Inside `practice`, create three subdirectories: `project1`, `project2`, `project3`.
    - Navigate into each subdirectory and create an empty file called `README.md` in each one.
2.  **Task 2: File Operations**
    
    - Create a file called `notes.txt` in `practice` with the content "Learning Linux is fun!".
    - Copy `notes.txt` to `project1` and rename it to `project1_notes.txt`.
    - Move `project1_notes.txt` from `project1` to `project2` and rename it to `final_notes.txt`.
3.  **Task 3: Understanding Permissions**
    
    - Create a new file called `secret.txt` in the `project3` directory.
    - Set the permissions so that only the owner can read and write to it.
    - Change the owner of `secret.txt` to another user (create a new user if needed).
4.  **Task 4: Process Management**
    
    - Open a new terminal and run `top`.
    - From another terminal, run a `ping google.com` command.
    - Find the `ping` process in `top` and terminate it using its `PID`.
5.  **Task 5: Basic Networking**
    
    - Check the IP address of the system using both `ifconfig` and `ip addr` commands.
    - Use `ping` to check the connectivity to `google.com`.
    - Use `netstat -tuln` or `ss -tuln` to list all listening ports on the machine.
6.  **Task 6: Package Management**
    
    - Install `curl` on the system.
    - Verify the installation by running `curl --version`.
    - Uninstall `curl` and then reinstall it.
7.  **Task 7: User Management**
    
    - Create a new user called `testuser`.
    - Add the user to the `sudo` group.
    - Switch to the new user using `su - testuser` and create a file in the `/tmp` directory.