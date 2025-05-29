# 19CS545-Ex8 - Create a user account in GitHub

# AIM:
To create a Repository

# Procedure:
1.The first command is: useradd -u 1326 alies
2.This command creates a new user account on the system. Here's a breakdown of the op ons used:
useradd: This is the command used to create a new user account. 2.-u 1326: This op on specifies the user ID (UID) for the new user account. The UID is a unique iden fier associated with each user account. In this case, the new user account will have a UID of 1326.
3.alies: This op on specifies the username for the new user account. The username is the name that the user will use to log in to the system.
4.The second command is: cat /etc/passwd | grep "alies"
5.This command is used to verify the informa on about the newly created user account. Here's a breakdown of the op ons used:
6.cat: This command is used to display the contents of a file. In this case, it's used to display the contents of the /etc/passwd file.
/etc/passwd: This file contains informa on about all user accounts on the system. Each line in the file contains informa on about one user account in the following format: username:password:UID:GID:full name or comment:home directory:default shell
7.grep "alies": This op on pipes the output of the cat command to the grep command. The grep command is used to search for a specific pa ern in the input. In this case, it's used to search for lines that contain the username "alies".
8.The third line in the image is a shell prompt, which indicates that the user is ready to enter another command.
9.In summary, these commands create a new user account named "alies" with a UID of 1326 and then verify the informa on about the newly created user account.

# Output:
![image](https://github.com/user-attachments/assets/36053288-5d21-4813-abc7-d416b0157dcd)

# Result:
Thus a Repository has been created successfully.
