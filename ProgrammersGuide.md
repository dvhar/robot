# robot
group project repo

How to Turn Nao On:
1. Hold down the button on his chest for about 10 seconds.
    -If he begins lighting up, and starts talking, he is on.
    -If he doesn't, he may be dead. Try plugging his charger in, and try step one again.
        *You should charge him for at least 90 minutes before using him. 
2. After he's turned on, he will tell you his IP address.

    -Write that down, you will need it.
3. Connect Nao to your computer's network and type the IP address he tells you into your browser's address bar.

    -You have to ensure he's registered before you can download the choregraphe software.
4. This robot should already be registered, but to login to the site use:
     -username: nao
5. Press connect
    
To Connect Nao to Your Computer:
1. Give your ethernet port an IP address with the same subnet as Nao's.

On windows:
1. control panel
2. network and sharing center
3. change adapter settings
4. pick an interface
5. properties
6. internet protocol v4
7. properties
8. enter ip address and netmask

On Linux:
1. open terminal
2. find out your interface name:
    ifconfig
3. give that interface an ip address:
    sudo ifconfig \<interface name\> \<ip address\> netmask 255.255.0.0

How to Download Choregraphe:
1. In order to download Choregraphe, Nao has to be registered.
2. Go to http://doc.aldebaran.com/2-4/dev/community_software.html#retrieving-software
3. Click the link in step 2.
4. You will need the above email and password to access the download. *******DID WE USE THE SAME USERNAME AND PASSWORD TO REGISTER??
5. Follow the directions to download the program.
6. When you're able to open it, it will ask for an activation code.
    -copy and paste the activation code:
7. After you type in the activation code, you will be on the home page of the Choregraphe application. 

How to do a Basic Choregraphe project:
1. Open your choregraphe application
2. Click "New Project"
3. There should be a virtual robot in the bottom right corner. If not:

    -click connection in the top left corner
        
    -click connect to
        
    -click the desktop robot
        
    -if that doesn't work, try exiting out of choregraphe and try again
        
4. On the left side of the screen, there should be a box with libraries of actions. If not:

    -click view in the top left corner
        
    -click the first option: "box libraries"
        
5. Click and drag the say option to the middle of the screen
6. Double click the "say" box, it will bring you to a localized text box
7. Here, you can change the language, and pick what you want him to say
8. Type "Hello humans!" into the localized text box
9. Click root to go back to the main project
10. Click the small box in the left hand corner with the black arrow
11. Drag the "noodle" from the first small box to the small box with the black arrow on the "say" box
12. To run your program, click the green arrow at the top
13. If nothing happens, don't worry. The virtual robot will not talk through your speakers. To make sure it's working, open the dialog box
14. To open the dialog box, click view, then click the dialog box option
15. Try running your program again, "Hello humans!" will pop up in the dialog box*
    *when you connect the real robot to your computer, he will say it out loud
16. Don't forget to save your project. Click file, then save project as...




How to make a project/combine projects
How to upload projects onto robot
