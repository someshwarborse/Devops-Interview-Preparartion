## Day 0 - Warmup Mock Interview Answers

Q1.
👉 What is the difference between a Process and a Thread in Linux?

Answer:

Process:
A process is a program that is currently being executed. It has its own memory space and resources, and multiple processes do not share memory.

Thread:
A thread is the smallest unit of execution within a process. All threads within the same process share the same memory space and resources, making them more lightweight compared to processes.

Q2.
👉 Explain what happens internally when you type ls -l in your Linux terminal and press Enter.

Answer:

ls is a command that lists the contents of a directory.

-l is an option that tells the ls command to display detailed information (such as permissions, owner, file size, and modification time).

Process:

The terminal interprets the command and passes it to the shell (Bash).

The shell looks for the ls command in the system’s PATH and executes it.

The ls command queries the directory for its contents.

It gathers information about each file (e.g., permissions, owner, size).

The data is returned to the terminal and displayed to the user in a human-readable format.

Q3.
👉 What is the use of the chmod command? Can you explain with a simple example?

Answer:

The chmod command in Linux is used to change the file permissions (read, write, execute) for users.

Example:

chmod 755 myscript.sh
This gives the owner read, write, execute permissions (7), and gives the group and others read and execute permissions (5 for group, 5 for others).

Explanation of 755:

The first digit (7) represents the owner's permissions: read (4), write (2), execute (1) = 7.

The second and third digits (5 each) represent group and others' permissions: read (4), execute (1) = 5.

Q4.
👉 Why do we use SSH in DevOps? Can you tell me the basic flow of how SSH connection happens?

Answer:

SSH (Secure Shell) is a protocol used for securely connecting to remote servers and executing commands over a network.

Why SSH in DevOps?

Secure Remote Access: Allows secure login to remote systems without exposing sensitive data.

Automation & Scripting: Enables automating tasks like server configuration, deployment, etc.

Encryption: Ensures that all data transmitted over the connection is encrypted and secure.

Basic Flow of SSH Connection:

Initiation: You initiate the connection by using the command ssh user@hostname.

Authentication: SSH checks if the server has the public key of the client, or it prompts for a password.

Connection: If the authentication is successful, the secure connection is established.

Data Transfer: Commands can now be securely executed on the remote server.

Q5.
👉 In your own words — what is DevOps? Explain it like you’re explaining it to a college friend who doesn’t know much about IT.

Answer:

DevOps is a set of practices that combines software development (Dev) and IT operations (Ops) to shorten the development lifecycle and improve the delivery of high-quality software.

In Simple Terms:
Imagine you're working on a project with a team, and each team member writes some code. Normally, this takes a long time to go live, and there are many things that can go wrong. DevOps is like a set of tools and methods that help developers and operations teams work together better to make sure the software gets to the users faster, with fewer bugs, and is easier to maintain.

# Summary of Answers for Your Document:

Q1. What is the difference between a Process and a Thread in Linux?

Process is a program with its own memory space.

Thread is a lightweight unit of execution within a process, sharing memory with other threads in the same process.

Q2. Explain what happens internally when you type ls -l in your Linux terminal and press Enter.

The command is passed to the shell, which then executes it, queries the directory, and returns detailed file information to the terminal.

Q3. What is the use of the chmod command? Can you explain with a simple example?

The chmod command changes file permissions.

Example: chmod 755 myscript.sh sets the owner's permissions to read, write, execute and others to read, execute.

Q4. Why do we use SSH in DevOps? Can you tell me the basic flow of how SSH connection happens?

SSH provides secure remote login and command execution.

Connection flow: Initiation → Authentication → Secure connection → Data transfer.

Q5. What is DevOps?

DevOps is a set of practices that bridges the gap between software development and IT operations to deliver high-quality software quickly and reliably.

***************************************************************
