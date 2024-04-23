# Add and Manage Users with Linux Commands
## Objective
The Coursera Google Cybersecurity Professional Certification Course work provides practical cybersecurity skills. This guided project utilizes a virtual machine environment to familiarize cybersecurity professionals with access control administrative duties using CLI commands. Specifically, this project explores CLI commands such as user-group-other read-write-execute permissions for files and directories; display hidden files; add, remove, and assign users to groups; change ownership of files; and removing groups.

### Skills Learned
-Understand access control administration within a Linux file system, utilizing CLI commands
-CLI commands:
<p>--display all files (-l), including hidden file (-a) (ls -la)</p>
<p>--user-group-other read-write-execute permissions for files (chmod u-/+ rwx,g-/+ rwx,o-/+rwx file)</p>
<p>--user-group-other read-write-execute permissions for files (chmod u-/+ rwx,g-/+ rwx,o-/+ rwx directory)</p>
<p>--add user (sudo useradd username)</p>
<p>--remove user (sudo userdel username)</p>
<p>--assign users to groups (sudo usermod -g group)</p>
<p>--assign users to secondary groups (sudo usermod -a -G second group username)</p>
<p>--change ownership of files (sudo chown username filepath)</p>
<p>--remove groups (sudo groupdel username) <i>*a default group is assigned to new usernames added to a linux file system</i></p>

### Tools Used
-Laptop
<p>-Coursera Google Cybersecurity Professional Certification Course</p>

### Steps
<img src="https://i.imgur.com/h5wrvUi.png" style="width: 45%;" alt="1">
<p><i>Ref 1: Example of CLI commands ls -la and various chmod examples</i></p>

Chmod commands are formatted as such where the the entities are represented by "u, g, or o" (user, group, other), seperated by a comma, and accompanied by a letter argument representing either a read, write, or execute ("r, w, x") function to modify an entities' permissions to gain access to files or directories, denoted by either "+" (add) or "-" (remove) to that permission.

<img src="https://i.imgur.com/8Fkdg7y.png" style="width: 65%;" alt="1">
<p><i>Ref 2: Various add, remove, and assignment CLI commands</i></p>

User adminstration commands are prefaced with "sudo" to grant temporary root access abilities to prevent unnecessary privilege escalations. "-g" and "-G" arguments denote group assignment, accompanied by group and username. "-a" arguments prefixes "-G" to assign a username to a second group.
