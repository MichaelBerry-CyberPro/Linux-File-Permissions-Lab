# Linux-File-Permissions-Lab

### Objective 
Demonstate managing file permissions and ownership using chmod, chown, and group

### Skills Demonstrated
1) chmod (numeric and symbolic)
2) chown and chgrp
3) Understanding rwx permissions
4) Principle of least privilege

### Scenario  
A shared project directory requires different access levels for developers and auditors

###Commands Used
bash
sudo chown dev_lead:developers project/
chmod 750 project/
