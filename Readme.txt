Install notes:

-Powerbuider works as a standalone, but If you already have MS Visual Studio 2010 (legal or with the hosts file tweaked) it will integrate a shell into it. Only, it needs it to have the SP1. So take a minute and update it to SP1 now, before installing the powerbuilder.

-For XP: It needs the IIS to have been pre-installed. 
This is a simple matter if you have just installed a fresh new XP copy: simply run the installation disk one more time and select Install optional Windows Components. Check the Internet Information Services (IIS) and you are done. 
But if you have your XP for a while, it will not run so smoothly: At one point it may ask you to direct it to the installing disk drive:\i386. Just do it. After a while it will ask for 33 items that are nowhere to be found (htm, gifs, etc.). I have prepared a folder (IIS_helper) where I have placed empty text files of these files. Direct it there. After that, it will ask you to direct it back to the installing disk:\i386\Cab1. Just do it. The bogus files it turns out, were needed only for installation, they do not show up in the operation anywhere.

-Proceed to insall powerbuilder, first the prerequisites, then the program itself At the prerequisites, it integrates a shell into VS10 (if you have it). Remember do not be quick on the trigger, databases take a long time to install - and do not start any components before the whole installation is over and asks for a restart.

-After the installation, copy the (supplied) dll into:
C:\Program Files\Sybase\Shared\PowerBuilder
It will still say Evaluation and Test, but goes on and works forever.

