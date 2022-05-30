# ALX - 0x01. Shell, permissions
All about bash projects
## Author
Kireshchand Dhanasar

## Tasks

0. Hello World

Write a script that prints Hello, World, followed by a new line to the standard output.

1. Confused smiley

Write a script that displays a confused smiley "(Ôo)'.

2. Let's display a file

Display the content of the /etc/passwd file.

3. What about 2?

Display the content of /etc/passwd and /etc/hosts

4. Last lines of a file

Display the last 10 lines of /etc/passwd
Example:

$ ./4-lastlines
_assetcache:*:235:235:Asset Cache Service:/var/empty:/usr/bin/false
_coremediaiod:*:236:236:Core Media IO Daemon:/var/empty:/usr/bin/false
_launchservicesd:*:239:239:_launchservicesd:/var/empty:/usr/bin/false
_iconservices:*:240:240:IconServices:/var/empty:/usr/bin/false
_distnote:*:241:241:DistNote:/var/empty:/usr/bin/false
_nsurlsessiond:*:242:242:NSURLSession Daemon:/var/db/nsurlsessiond:/usr/bin/false
_nsurlstoraged:*:243:243:NSURLStorage Daemon:/var/empty:/usr/bin/false
_displaypolicyd:*:244:244:Display Policy Daemon:/var/empty:/usr/bin/false
_astris:*:245:245:Astris Services:/var/db/astris:/usr/bin/false
_krbfast:*:246:-2:Kerberos FAST Account:/var/empty:/usr/bin/false


5. I'd prefer the first ones actually

Display the first 10 lines of /etc/passwd

Example:

$ ./5-firstlines
##
# User Database
#
# Note that this file is consulted directly only when the system is running
# in single-user mode. At other times this information is provided by
# Open Directory.
#
# See the opendirectoryd(8) man page for additional information about
# Open Directory.
##
$
6. Line #2

Write a script that displays the third line of the file iacta.

The file iacta will be in the working directory

Youre not allowed to use sed
julien@ubuntu:/tmp/h$ cat iacta 
Alea iacta est

Alea iacta est ("The die is cast") is a Latin phrase attributed by Suetonius
(as iacta alea est) to Julius Caesar on January 10, 49 BC
as he led his army across the Rubicon river in Northern Italy. With this step,
he entered Italy at the head of his army in defiance of the Senate and began
his long civil war against Pompey and the Optimates. The phrase has been
adopted in Italian (Il dado è tratto), Romanian (Zarurile au fost aruncate),
Spanish (La suerte está echada), French (Les dés sont jetés), Portuguese (A
sorte está lançada), Dutch (De teerling is geworpen),
German (Der Würfel ist gefallen), Hungarian (A kocka el van vetve) and many other languages to
indicate that events have passed a point of no return.

Read more: https://en.wikipedia.org/wiki/Alea_iacta_est
julien@ubuntu:/tmp/h$ ./6-third_line 
Alea iacta est ("The die is cast") is a Latin phrase attributed by Suetonius
julien@ubuntu:/tmp/h$ 
Note: The output will differ, depending on the content of the file iacta.

7. It is a good file that cuts iron without making a noise

Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

8. Save current state of directory

Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

9. Duplicate last line

Write a script that duplicates the last line of the file iacta

The file iacta will be in the working directory

10. No more javascript

Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

11. Don't just count your directories, make your directories count

Write a script that counts the number of directories and sub-directories in the current directory.

The current and parent directories should not be taken into account
Hidden directories should be counted

12. Whats new

Create a script that displays the 10 newest files in the current directory.

Requirements:

One file per line
Sorted from the newest to the oldest

13. Being unique is better than being perfect

Create a script that takes a list of words as input and prints only words that appear exactly once.

Input format: One line, one word
Output format: One line, one word
Words should be sorted

14. It must be in that file

Display lines containing the pattern root from the file /etc/passwd

15. Count that word

Display the number of lines that contain the pattern bin in the file /etc/passwd

16. What's next?

Display lines containing the pattern root and 3 lines after them in the file /etc/passwd.

17. I hate bins

Display all the lines in the file /etc/passwd that do not contain the pattern bin.

18. Letters only please

Display all lines of the file /etc/ssh/sshd_config starting with a letter.

include capital letters as well

19. A to Z

Replace all characters A and c from input to Z and e respectively.

20. Without C, you would live in hiago

Create a script that removes all letters c and C from input.

21. esreveR

Write a script that reverse its input.

22. DJ Cut Killer

Write a script that displays all users and their home directories, sorted by users.

Based on the the /etc/passwd file


