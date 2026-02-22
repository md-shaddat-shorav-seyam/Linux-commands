# Linux-commands

---

## 1. Navigating the Filesystem

In Linux, everything is a file. These commands help you move around and see what's what.

* **`ls`**: Lists directory contents.
* `ls -l`: Shows detailed info (permissions, size, owners).
* `ls -a`: Shows hidden files (those starting with a dot).


* **`cd`**: Changes the current directory.
* `cd ..`: Move up one level.
* `cd ~`: Go to your home directory.


* **`pwd`**: "Print Working Directory"—shows exactly where you are in the tree.

---

## 2. File & Directory Manipulation

The bread and butter of terminal work.

* **`mkdir`**: Creates a new directory.
* **`touch`**: Creates an empty file or updates the timestamp of an existing one.
* **`cp`**: Copies files or directories.
* `cp -r`: Required to copy directories recursively.


* **`mv`**: Moves or **renames** files.
* **`rm`**: Removes files.
* **Caution:** `rm -rf` deletes directories and their contents permanently without a trash bin. Use with extreme care.



---

## 3. Reading & Searching Files

You don't always need a heavy editor like Vim to see what's inside a file.

* **`cat`**: Concentrates and displays file content. Great for short files.
* **`less`**: Opens a file for interactive reading (allows scrolling). Press `q` to exit.
* **`grep`**: The ultimate search tool. It finds text patterns within files.
* `grep "error" log.txt`: Finds every line containing "error".


* **`find`**: Searches for files based on name, size, or time.

---

## 4. System Info & Permissions

Linux is a multi-user system, so permissions are everything.

* **`chmod`**: Changes file permissions (e.g., `chmod +x script.sh` makes it executable).
* **`chown`**: Changes file ownership.
* **`sudo`**: "SuperUser Do"—runs a command with administrative privileges.
* **`top` / `htop**`: Displays real-time system processes, CPU, and RAM usage.

---

## 5. Network & Connectivity

* **`ip addr`**: Shows your IP addresses and network interfaces.
* **`ping`**: Checks connectivity to a server.
* **`curl` / `wget**`: Downloads files or interacts with URLs directly from the command line.
* **`ssh`**: Securely connects you to a remote Linux machine.

---

### 💡 Pro-Tip: The "Manual" Command

If you want the "full documentation" for *any* specific command, Linux has a built-in encyclopedia called **man pages**.

Just type:
`man <command_name>`

For example, `man grep` will show you every single flag and feature available for grep.

---

