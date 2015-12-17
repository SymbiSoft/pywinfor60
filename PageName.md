Pywinfor symbian google page.
# Introduction #

Here iam telling how iam going to make it

# Details #
I made this using python programing langauge.

java,flash,symbian,m,fshell, and all other language apps can use my window system becasue i used socket.
Every language can access internet so my window system is available in windowsystem.com in port 6000.


**From user point**

Window system is an installable application.
it automaticaly run on switch on.
It must run in background.
It uses an asseccpoint but it will never connect to internet.
It act as local server.



**from developer view**

this is a window system looks like xwindow system of linux.

It is acting as a server because it use socket.and socket.bind
it wait for connection from another application in this mobile.

When an client app connect.we make a window using topwindow module.

And show it in screen.

**example Process**

Every client apps (which app need window).start a socket connection to 'windowmanager.com' port 6000. (this amy change)

And send some commands (comands currently not writen )
to server.

Server make a window and show it in screen.

Commands are many types.4 types

Requst,responce,error,event

Request
> A client send to server (i want a window or i want draw part of window)
Responec
> Server to client.
> (hay client app i made window you requested)

Event
> server to client
> (hay client app a key pressed )
Error
> > Server to client
> > (hay client i cant make window you requested)

Here i give comand overview.realy i need to write correct order of comands


**from python developr view**

I used socket module to act as server.
And bind in windowmanager.com port 6000
Socket.listen(20) window man only provide maximum 20 connection or ram will full.
this is changable.