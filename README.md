# LinuxExam_Friday13thMay

A part checking your Linux skills, during the exam you will download the dataset you need for the first part of the course *Working with bacterial communities*. The exam will be performed directly on your CSC account where you will perform all the activities of the course. Below you will find some general instructions on how to connect to your csc account through your computer.

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
