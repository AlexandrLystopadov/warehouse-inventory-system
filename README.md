### Installing application is fairly easy, just follow these steps:
1. Install Ansible
    
2. Creating inventories to track a list of servers
    
3. Execute apache and mysql playbooks
    
4. Import/load oswa_inv.sql into your mysql database. This should set up the basic structure of the database system.
    
5. Modify the includes/config.php and change the variables to match your host, database, username and passwords.
    
6. Execute php playbooks
    
7. Change all Folder permission inside uploads folder either add them to group call `www` if available or `777`.
    
8. Then loging by typing **username** and **password**:
    
    |Administrator|Special User|Default User|
    |---|---|---|
    |**Username** : admin|**Username** : special|**Username** : user|
    |**Password** : admin|**Password** : special|**Password** : user|
    
6. Good luck!

