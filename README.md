# Shrusti
linux commands assignment



activity
1
+ Activity-1 → ls command options
2
+ Using man ls, here are the
explanations for the flags
3
mentioned:
+· ls -b → Prints non-
printable characters in file
names as octal escape sequences
(\xxx).
4
ls -c → Sorts files by
ctime (last status change)
instead of modification time.
Also affects -lt.
5
+ · ls -d → Lists only
directory entries themselves,
not their contents (e.g., ls -d
/etc just shows /etc).
6
+ • ls -e → On some systems,
shows access control list (ACL)
7
info (like ls -l --time=atime).
+ • ls -f → Displays directory
contents unsorted (as they are
stored). Also implies -a (show
8
hidden files).
ls -z > Shows SELinux
security context for files
(useful in security-enabled
systems).

ls -z → Shows SELinux
security context for files
(useful in security-enabled
9
systems).
+
10
+ Other commands to explore (do
11
on terminal)
whoami → Prints your
12
current logged-in username.
+· pwd → Shows the current
working directory.
13
cd → Changes directory.
14
+·
cd /→ Moves you to the
root directory.
15
cd ..→ Moves you one level
16
up (to the parent directory).
cd <path>→ Moves you to
the specified path.
17
+
18
+ Activity-2 > tree command
19
options
20
+ Using man tree:
tree -a → Shows all files
including hidden ones (those
starting with .).
github.com - Private

+
cd / → Moves you to the
15
root directory.
cd ..→ Moves you one level
up (to the parent directory).
16
cd <path>→ Moves you to
17
the specified path.
18
+ Activity-2 → tree command
19
options
+ Using man tree:
20
tree -a → Shows all files
including hidden ones (those
21
starting with .).
tree -d → Lists only
22
directories.
tree -u > Shows the file
23
owner's username.
tree -p → Shows permissions
(rwx)for each file/directory.
24
