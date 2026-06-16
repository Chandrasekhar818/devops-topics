Check permissions:

ls -l

Example:

-rwxr-xr--

Breakdown:

Owner  Group Others
rwx    r-x   r--

Meaning:

Symbol	Meaning
r	Read
w	Write
x	Execute
Change Permissions
chmod 755 script.sh

Explanation:

7 = rwx
5 = r-x
5 = r-x
Change Ownership
chown user:user file.txt
