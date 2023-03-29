# born2beRoot

![image](https://user-images.githubusercontent.com/116757689/228551464-393aba75-8a6c-4c8f-9bcd-d3c2016389c6.png)


this project is about making a Virtual Machine, it's quite easy if you just follow the guide, the hard part is passing the evaluation since there is no moulinette and you have to convince other of you deep understaind of the project, you peers will fail you if you are not able to answer some. questions

# **YOUTUBE VIDEO**

[![introductio to virtual Machine](https://ytcards.demolab.com/?id=wX75Z-4MEoM&ab_channel=NetworkChuck&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=250&duration= "virtual machine")](https://youtu.be/wX75Z-4MEoM)[![introductio to virtual Machine](https://ytcards.demolab.com/?id=ORcvSkgdA58&ab_channel=Computerphile&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=250&duration= "ssh protocol")](https://youtu.be/ORcvSkgdA58)

# SSH EXPLANATION:

SSH stands for "Secure Shell." It's a way to connect to a computer securely from another computer over the internet. Imagine you're sending a secret message to a friend, but you don't want anyone else to be able to read it. You could put the message in a box and lock it with a key. You would send the box to your friend, and they would unlock it with their own key to read the message.

SSH works in a similar way. It uses a special encrypted channel to allow you to remotely connect to a computer, like the one you might use at work or school. This makes sure that nobody else can see what you're doing, and that your connection is secure. The client-server paradigm means that your computer is the client, and the computer you're connecting to is the server. The two communicate through this secure channel to keep your information safe.

![image](https://user-images.githubusercontent.com/116757689/228550743-7489f5c1-7d46-482b-a9bd-3405b831eac3.png)


**SSH KEY OF GITHUB? IS THE SAME THING?**

Yes, the SSH protocol used for secure remote access to a server is the same protocol used for authentication and secure communication with your GitHub account.

When you generate an SSH key on your computer and add the public key to your GitHub account, it allows you to securely authenticate with GitHub and perform operations like pushing changes to a repository without needing to enter your username and password every time. The SSH key is used as a secure and convenient way to verify your identity to GitHub.

# UFW  EXPLANATION:

Ufw stands for Uncomplicated Firewall, and is a program for managing a netfilter firewall. It provides a command line interface and aims to be uncomplicated and easy to use. Note: It should be noted that UFW can use either iptables or nftables as the back-end firewall.

Think of your computer like a house, and the internet like a busy street. Just like you have a front door to your house, your computer has ports that allow traffic to come in and out. UFW is like a security system for your computer's ports, making sure only the right traffic gets in and out.

![image](https://user-images.githubusercontent.com/116757689/228550930-b7b6f284-5763-41b9-8366-0538fe5e9137.png)


It works by using a set of rules that determine which traffic is allowed through each port, based on factors like the source of the traffic, the type of traffic, and other conditions. These rules are managed through a command-line interface, which lets you easily control and monitor your computer's firewall.

Overall, UFW is an important tool for keeping your computer and its data safe from unauthorized access, just like a security system keeps your house and belongings safe from intruders.

# SUDO POLICY EXPLANATION:

In Linux, there is a special command called "sudo" that allows a regular user to execute commands as a superuser (also known as "root"). This is very powerful because it gives the user access to system-level functions that can affect the entire computer.

However, it's important to use sudo carefully and make sure that only authorized users can access it. To do this, we can create a sudo policy, which is a set of rules that specify who can use sudo and what commands they can execute.

![image](https://user-images.githubusercontent.com/116757689/228551220-9601dda3-95d2-43e2-832c-bb9f0e41f129.png)


In this section, we are creating a file called "sudo_config" in a special directory called "/etc/sudoers.d/". This file will contain our sudo policy. The command "touch" is used to create an empty file. Once the file is created, we can edit it to add our policy rules.

Think of it like a locked safe where only authorized people have the combination to open it. The "sudo_config" file is like the combination that grants access to the powerful "sudo" command.


# 😎copy and paste on virtual machine😎


##  ( my friend [Osema](https://github.com/OsemaFadhel) helped me )

open the Mac terminal, write this command:

```
ssh <user>@localhost -p 4242
```

 you will ask for the password. 
 <img width="638" alt="image" src="https://user-images.githubusercontent.com/116757689/228546369-3d1016a6-64f3-4650-9fb1-8a2620b43930.png">

