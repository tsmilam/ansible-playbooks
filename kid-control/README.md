# You're grounded!
This very simple playbook has been tested on Windows 10. It will disable the child's account. It may be more effective than Microsoft Family controls if your child is a gifted social engineer.

The computer is rebooted after disabling the account as a simple means of forcing the change to be immediately effective, otherwise any existing logon session will continue. 

You and your child may notice that the computer account is not visible from the logon screen once this playbook is executed with `account_disabled` set to `yes`. The account is still there, simply disabled. To reenable it, run the playbook again with `account_disabled` set to `no`. 