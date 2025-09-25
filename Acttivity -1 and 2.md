Acttivity -1
part 1
man ls -b

Description: Print non-graphic characters in file names as octal escape sequences (\xxx).
(shrusti-miskin@lax06:~) $
$ ls -b
Desktop Documents Downloads hash.txt hello\010o.txt


man ls -c

Description: Sort files by ctime (time of last status change) instead of modification time. When listing long format (-l), show ctime.
(shrusti-miskin@lax06:~) $
$ ls -c
hi Downloads hash.txt hellooo.txt Desktop


man ls -d

Description: Lists only directory entries themselves, not their contents (e.g., ls -d /etc just shows /etc).
(shrusti-miskin@lax06:~) $
$ ls -d */
Desktop/ Documents/ Downloads/


man ls -f

Description: Displays directory contents unsorted (as they are stored). Also implies -a (show hidden files).
(shrusti-miskin@lax06:~) $
$ ls -f
file2.txt folder/ file1.txt


man ls -z

Description: Shows SELinux security context for files (useful in security-enabled systems).
(shrusti-miskin@lax06:~) $
$ ls -z
unconfined_u:object_r:user_home_t:s0 file1.txt

---

Other commands to explore (do on terminal)

whoami -> Prints your current logged-in username.
pwd -> Shows the current working directory.
cd -> Changes directory.
cd / -> Moves you to the root directory.
cd .. -> Moves you one level up (to the parent directory).
cd <path> -> Moves you to the specified path.

---

Activity 2 -> tree command options
Using man tree:

tree -a -> Shows all files including hidden ones (those starting with .).
(shrusti-miskin@lax06:~) $
$ tree -a
.hiddenfolder
file.txt

tree -d -> Lists only directories.
(shrusti-miskin@lax06:~) $
$ tree -d
folder1
folder2

tree -u -> Shows the file owner's username.
(shrusti-miskin@lax06:~) $
$ tree -u
drwxr-xr-x user folder1

tree -p -> Shows permissions (rwx) for each file/directory.
(shrusti-miskin@lax06:~) $
$ tree -p
drwxr-xr-x folder1
-rw-r--r-- file1.txt