# snowflake-tasks

users with the MONITOR role have the permissions to view and monitor tasks that are running in the account. This includes the ability to view the status and details of tasks, as well as to cancel tasks if needed.

To grant the MONITOR role to a user, you can use the GRANT command, like this:

Copy code
GRANT MONITOR TO USER my_user;
Alternatively, you can grant the MONITOR role to a user as part of a larger role, such as the ACCOUNTADMIN role, which includes all privileges in the account.

To view and monitor tasks in Snowflake, you can use the SHOW TASKS command, which will display a list of all tasks that are currently running in the account. You can also use the DESCRIBE TASK command to view more detailed information about a specific task, including the task type, status, and start and end times.

It's important to note that the MONITOR role does not grant the ability to create, modify, or delete tasks. To perform these actions, users will need additional privileges, such as the SECURITYADMIN or SYSADMIN role.
