# Getting Started
## Installing Visual Studio Code
First go to the Visual Studio code website https://code.visualstudio.com/. Follow the instructions on the site.

When installed you should see a window that looks similar to this:

<img width="1022" alt="Screenshot 2023-04-08 at 11 56 26 AM" src="https://user-images.githubusercontent.com/32113345/230738495-45cf2ad2-21c3-4a61-ad1f-55e9b9b5bbbc.png">

## Remotely Connecting
Let's start by connecting to a **remote server**

`$ this is a command to the remote server`

If this is your first time connecting to this server you might get a message that looks similar to this:
`⤇ ssh cs15lsp23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? `

Type "yes"

You should see something that looks like this
\
`# Now on remote server
Last login: Sun Jan  2 14:03:05 2022 from 107-217-10-235.lightspeed.sndgca.sbcglobal.net
quota: No filesystem specified.
Hello cs15lsp23zz, you are currently logged into ieng6-203.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   23:25:01   0  0.08,  0.17,  0.11
ieng6-202   23:25:01   1  0.09,  0.15,  0.11
ieng6-203   23:25:01   1  0.08,  0.15,  0.11`

## Lets run some commands!
Here are some great commands to get started!
>`cd ~`,
>`cd`,
>`ls -lat`,
>`ls -a`,
>`ls <directory>`, 
> Also try running a command to read a text file!

To log out of the server, you can run
> Ctrl-D or 
> Run command exit
