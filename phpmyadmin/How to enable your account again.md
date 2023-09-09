# Account is disabled and how to fix.

Lots of people may have typed the wrong password for their GDPS account when trying to log in.
You probably got "account is disabled" when you typed in the right password and clicked login.
Don't worry, you can enable it again by doing the following;

First, login to PhpMyAdmin.
After logging in, navigate to the "accounts" table.
In "accounts" table, look for your account, then look for "accountID."
Once you have got your account ID, navigate to the "actions" table.
In the "actions" table, delete the action with the ID of your account.
Now, your account will be enabled again!
