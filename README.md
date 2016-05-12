# LinuxExam_Friday13thMay

A part checking your Linux skills, during the exam you will download the dataset you need for the first part of the course *Working with bacterial communities*. In addition, we will have the opportunity to check if you had installed all the required software and that your csc account is working. In fact, the exam will be done directly on your CSC account where you will perform all the activities of the course. Below you will find some general instructions on how to connect to your csc account through your computer.

##The exam
To start the exam download the word document *Unix_test.docx* (right click > save link as) follow the instructions, feel the boxes, save the document including your name in the filename and send it to mirko.rossi@helsinki.fi and jenni.hultman@helsinki.fi by today at 13:00.

##How to access you CSC account
###For *Mac* or *Linux* users

Open the *terminal*. You can search it by typing "terminal" in the "search box" (top right of your screen).

In the terminal type

```
ssh <useraccount>@taito.csc.fi
```

Then type your password and you will be at your $HOME directory in Taito.

For closing the session type

```
exit
```

###For *Windows* users

If you had installed a ssh client software open it. For this example I'm assuming you are using Putty. 
In "Host Name" type

```
<useraccount>@taito.csc.fi
```

"Port" should be 22 and "Connection type" should be "SSH". Click "Load". If it is the first time, a window will pop-up asking to verify the connection. Accept. A terminal window will open where you must insert your password and you will be at your $HOME directory in Taito.

For closing the session type

```
exit
```

###For all users
If you don't want install a local ssh terminal program, you can use the SSH console tool in Scientist's User Interface (https://sui.csc.fi/). Launch the *SSH Console* by clicking the icon in the *Services Desktop* or by selecting the tool from the *Services Menu*. When the console is launched, it asks for your user account and the name of the server you want to connect. The password will be asked only later on. Type

```
Username: <csc_username>
Remote Host: taito.csc.fi
```
When the Java based console program starts you may need to accept launching the process in you local machine and allow the process connect CSC. When the console is running it will ask you to choose the authentication method to be used. 

```
Select: password and press Proceed.
````

After this a Password Authentication window opens. Type in you password and press OK. 
You can use the console to use the CSC servers, but it contains also other tools than just the command line client. You can use it for example for file transport or secure tunneling of server ports. In the case of file transport you can utilize the SFTP file transport tool.
