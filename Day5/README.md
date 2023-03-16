After finishing the #day4task of basic shell scripting. Let’s deep dive into advanced shell scripting for DevOps Engineers.

Here is lists of tasks and solutions-

    Write a bash script createDirectories.sh that when the script is executed with three given arguments (one is directory name and second is start number of directories and third is the end number of directories ) it creates specified number of directories with a dynamic directory name.

For this we can use for loop command.As it iterates through a range of values defined by “$2” and “$3,” this script will produce a number of folders with names created by appending the value of the variable “$1” with the value of the variable “$i.”

The script iterates through the range of values indicated by “$2” and “$3” using a “for” loop. The loop executes until the loop variable I is greater than “$3,” with I originally having the value “$2”. The “mkdir” command and the value of “$1” along with the value of I are used in the loop’s body to create a new directory.

![image](https://user-images.githubusercontent.com/91723005/225742496-9d9469c1-9a19-4959-9aad-e57d3a3b922b.png)


2.Read About Cron and Crontab, to automate the backup Script

Cron is a command line utility to run small and quick commands on a scheduled basis. This is a handy, classic sysadmin tool for automating various tasks by combining it with othe tools. For example, some people combine rsync and cron to automatically create a daily or weekly backup at a certain time. Some people use it to analyze server logs and combine it with mail function to send an email if there is certain kind of error detected in the logs.

Crontab stands for “cron table”.The crontab is a list of commands that you want to run on a regular schedule, and also the name of the command used to manage that list.Crontab fields and it’s ranges are-

    MIN (0-59)
    HOUR (0–23)
    DAY OF MONTH(DOM) (1–31)
    MONTH FIELD(MON) (1–12)
    DAY OF WEEK(DOW) (0–6)
    COMMAND TO BE RUN

3. User Management

User management is a process to create,modify and delete user from the system.In other words, user management has a ability to set passwords,add users,set permissions,manage networks etc.User management is an important aspect of system administration, as it allows you to control who has access to the system and what actions they are allowed to perform.

4.Create 2 users and just display their Usernames

We use sudo adduser username to create two different users and then display it with cat /etc/passwd command.
![image](https://user-images.githubusercontent.com/91723005/225742650-8b10f866-2644-4b4c-9a9a-efed35eb5eb8.png)
![image](https://user-images.githubusercontent.com/91723005/225742680-33f1c853-0ca6-4f34-84c0-89f858c4f16c.png)


