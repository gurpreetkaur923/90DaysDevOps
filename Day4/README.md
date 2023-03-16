After understanding the Linux commands now #day4task is all about shell scripting which is one of an integral part of Linux for automation the process.Let’s start the #day4task to understand more about what shell scripting is?How to write different scripts?What’s the importance of shell scripting in DevOps .

So,let’s find out the #day4task solutions which is related to shell scripting.

    -Explain in your own words and examples, what is Shell Scripting for DevOps.
    -What is #!/bin/bash? can we write #!/bin/sh as well?
    -Write a Shell Script which prints I will complete #90DaysOofDevOps challenge
    -Write a Shell Script to take user input, input from arguments and print the variables.
    -Write an Example of If else in Shell Scripting by comparing 2 numbers

What is Shell Scripting?

As the name implies, it is a script or program that is used to perform specific tasks.Shell scripting is an essential part of process automation in Linux. Scripting helps you write a sequence of commands in a file and then execute them.This saves your time because you don’t have to write certain commands again and again. You can perform daily tasks efficiently and even schedule them for automatic execution.Here are some examples of shell scripting:

    -Executing routine backups.
    -Manipulating files.
    -Monitoring a system
    -Regular stock price tracking
    -Automated airline checking system
    -Automatic mailers
    
   
   
   ![image](https://user-images.githubusercontent.com/91723005/225741466-dc0b2d3c-51ef-4e49-ae06-e2323a9b794a.png)


Basically,we can see shell script started with (#!/bin/bash or #!/bin/sh) line.So,what this line called?Why we use this in our script?Let’s understand it step by step…..

 (#!) is a combination of tokens in which (#)indicates sharp and (!) bang. It’s commonly known as “She-bang”.
  /bin/bash vs /bin/sh : It indicates shell which is not only responsible for little prompts but also interpreting the commands of the script. (/bin/bash) is most common shell used in shell scripting. It’s also known as “Bourne-again shell”. Bash can be used both for scripting and as an interactive terminal or interpreter. You can relate to this similar to how python3 is a scripting language and how it is an interpreter (when you type in python3 in the terminal, you can see an interactive interpreter. Bash in interactive mode is the terminal or the command prompt.(/bin/sh) indicates a system shell and a default shell the script should use.
    ![image](https://user-images.githubusercontent.com/91723005/225741727-57eb37d5-a7c4-46b2-8d73-b2b8cc0fa80f.png)


Write a Shell Script which prints I will complete #90DaysofDevOps challenge?

We can use “echo”command to print this message. The message should be enclosed with quotation mark(“……”). To run this script we can write ./filename.Remember, we only use .sh extension for scripts.
![image](https://user-images.githubusercontent.com/91723005/225741777-a7c997b9-82c0-4bc1-9dc9-d3d5a7ccc85c.png)


Write a Shell Script to take user input, input from arguments and print the variables.

Firstly,we take the user input. we use “echo” which prints a message to user to enter name then use “read” which gets the user input and store it in a variable.Second, we can pass the argument by $1 for first argument (Engineer) and stores into the profession variable. Third, print the variable with the “echo” command.
![image](https://user-images.githubusercontent.com/91723005/225741862-e859dae2-5e98-4364-b01b-13b657c1facf.png)

Write an Example of If else in Shell Scripting by comparing 2 numbers

To compare two numbers we use if else command in script. in which we give two arguments to compare with each other and then print it with “echo”command. In this script, if num1 is less than num2 than if block is executed otherwise else block executed when num1 is greater than num2.

![image](https://user-images.githubusercontent.com/91723005/225741905-a8043ff5-e5d0-4087-9c1e-22dfa37a38a2.png)
