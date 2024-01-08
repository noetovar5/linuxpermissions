<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=noetovar5.linuxpermissions"/>

# linuxpermissions
Learn linux permissions




Man chmod

User and group should have read and write and other no privilege's

Chmod G+W file3.txt

This will change group to have write on file3.

Chomod o-r file3.txt

This will take away from file3, they can no longer read

Ls -l file*

Chmod G+w,0-r file2.txt

This will change permission

Chomd u+X,G-rwx,o-rwx file2.txt

Now the top will allow user to have an executable while the group can read, write and execute and other has lost all rights

 
Another way is to use equals sign

For example
Chomd U=RW,G=RW,O-RWX FILE2.TXT

This means that user can read and write, the group can read and write and others can do nothing

To install ubuntu VM on your windows
Open up powershell as an admin
Then type in wsl --install

You will now have ubuntu on your windows machine

If I want to change the file to read, write and execute I could use 7 for example
Chomd 777 file2.txt!

