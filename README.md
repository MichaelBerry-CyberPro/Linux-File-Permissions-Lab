# Linux-File-Permissions-Lab

### Objective 
Demonstrate managing file permissions and ownership using chmod, chown, and group

### Skills Demonstrated
1) chmod
2) chown
3) Understanding rwx permissions
4) Principle of least privilege

### Scenario  
A shared project directory requires different access levels for developers and auditors

### Chmod Used
I used LS command verify the directory phoenix_project. I use Change Directory to get into the directory, created a new file with Touch. I used LS to confirm it was created and used to Chmod 600 to change read + write permission for the owner. I then verified that the command took place and executed properly with the appropriate permission.

![image alt](https://github.com/MichaelBerry-CyberPro/Linux-File-Permissions-Lab/blob/main/Change%20permissions.png)

### Change Ownshership
I used the Sudo Chown command to gain elevated control to change ownership.
![image alt](https://github.com/MichaelBerry-CyberPro/Linux-File-Permissions-Lab/blob/main/Change%20ownership.png)
