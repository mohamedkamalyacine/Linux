#Lab_2

1. Create a user account with the following attribute
- username: islam
- Fullname/comment: Islam Askar
- Password: islam
![Screenshot from 2022-11-23 15-10-13](https://user-images.githubusercontent.com/110255978/203644381-00c58f7e-ada6-4fe0-b8f6-706ab0e792e5.png)

2. Create a user account with the following attribute
- Username: baduser
- Full name/comment: Bad User
- Password: baduser
![Screenshot from 2022-11-23 15-13-23](https://user-images.githubusercontent.com/110255978/203644529-2aa3883c-85e3-4e82-b743-e07d5ed5d2af.png)

3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
![Screenshot from 2022-11-23 19-56-25](https://user-images.githubusercontent.com/110255978/203644610-9fdf4882-b29a-4047-88d8-a917f8d09cbc.png)

4. Create a supplementary group called badgroup
![Screenshot from 2022-11-23 19-59-14](https://user-images.githubusercontent.com/110255978/203644677-a626c3ea-09ca-4360-9bf8-dc3cd0718009.png)

5. Add islam user to the pgroup group as a supplementary group
![Screenshot from 2022-11-23 20-06-10](https://user-images.githubusercontent.com/110255978/203644755-bb4e0d69-7a6d-43a6-bd80-62f70bfba457.png)

6. Modify the password of islam's account to password
![Screenshot from 2022-11-23 20-11-42](https://user-images.githubusercontent.com/110255978/203644817-1c8f8c19-7f84-426b-a727-e37525a9c939.png)

7. Modify islam's account so the password expires after 30 days
![Screenshot from 2022-11-23 20-26-26](https://user-images.githubusercontent.com/110255978/203644888-1b2abd99-fded-483c-ab3c-88df086c7192.png)

8. Lock bad user account so he can't log in
![Screenshot from 2022-11-23 20-27-27](https://user-images.githubusercontent.com/110255978/203644991-0bd84b23-be25-40ce-9520-cda823e5ee36.png)

9. Delete bad user account
![Screenshot from 2022-11-23 20-29-23](https://user-images.githubusercontent.com/110255978/203645090-10c83bf8-2236-4c9a-97a9-70ab05eb1200.png)

10. Delete the supplementary group called badgroup.
![Screenshot from 2022-11-23 20-30-09](https://user-images.githubusercontent.com/110255978/203645141-b77f69d2-9e80-4655-ab0d-b31aee25f3a2.png)

13. Create a folder called myteam in your home directory and change its permissions to 
read only for the owner.
![Screenshot from 2022-11-23 21-16-32](https://user-images.githubusercontent.com/110255978/203645264-57112304-c811-41d4-ad9b-67d3fbc50570.png)

14. Log out and log in by another user
![Screenshot from 2022-11-23 21-25-01](https://user-images.githubusercontent.com/110255978/203645305-944dbe23-3c2b-425a-bf28-fc7c5c39ca81.png)

16. Using the command Line:
- Change the permissions of oldpasswd file to give owner read and write 
permissions and for group write and execute and execute only for the others 
(using chmod in 2 different ways)
![Screenshot from 2022-11-23 21-36-42](https://user-images.githubusercontent.com/110255978/203645668-767d33b1-0411-4d78-839b-3b47154fb347.png)

- Change your default permissions to be as above.
![Screenshot from 2022-11-23 21-39-45](https://user-images.githubusercontent.com/110255978/203645715-c839e026-9752-41c8-90dc-48bffb30ab58.png)

- What is the maximum permission a file can have, by default when it is just 
created? And what is that for directory.
Max permission of a file --> 666 ( rw-rw-rw-)
Max permission of a folder --> 777 ( rwx-rwx-rwx)

- Change your default permissions to be no permission to everyone then create a 
directory and a file to verify
![Screenshot from 2022-11-23 22-22-16](https://user-images.githubusercontent.com/110255978/203646098-7d195508-a489-4cb6-9a68-5421ce179457.png)

17. What are the minimum permission needed for:
- Copy a directory (permission for source directory and permissions for target 
parent directory)
source directory: execute and read permission
target directory: execute and write permission.

- Copy a file (permission for source file and and permission for target parent 
directory)
source file: read permission.
target file: dosn't need any permission since it doesn't exit before you copy it, or write permission if the file exists

- Delete a file
To delete a file requires both write (to modify the directory itself) and execute (to stat() the file's inode) on a directory

- Change to a directory
write & execute 

- List a directory content (ls command)
read

- View a file content (more/cat command)
read

 - Modify a file content
 wirte, read & execute

18. Create a file with permission 444. Try to edit in it and to remove it? Note what 
happened
![Screenshot from 2022-11-23 22-32-38](https://user-images.githubusercontent.com/110255978/203647572-cec57e33-073a-4a84-a941-0954cd0fb487.png)
![Screenshot from 2022-11-23 22-33-25](https://user-images.githubusercontent.com/110255978/203647581-6e3da60d-1cc3-44dc-a672-3b74ab02b8f9.png)


19. What is the difference between the “x” permission for a file and for a 
directory?
Execute permission on files means the right to execute them, if they are programs. For directories, execute permission allows you to enter the directory and to access any of its files










