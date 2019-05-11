# Nao Robot Programming Guide

How to Turn Nao On:
<ol>
<li> Hold down the button on his chest for about 10 seconds. If he begins lighting up, and starts talking, he is on. If he doesn't, he may be dead. Try plugging his charger in, and try step one again.</li>
        *You should charge him for at least 90 minutes before using him. 
       <li> After he's turned on, he will tell you his IP address. If he doesn't, press the chest button again and he will.</li>
<li> Connect Nao to your computer's network and type the IP address he tells you into your browser's address bar. Do this with ethernet, and from there you can connect him to wifi if you want. You will need to login with username and password. </li>
       
       -username: nao
       -password: beget579\[delete

</ol>

___
    
How to Connect Nao to Wifi:
<ol>
       <li>After you login with his IP address, select one of the available WiFi networks.</li>
       <li>Complete the required parameters, and click the connect button.</li>
 </ol>
 
___
    
If your computer doesn't automatically connect to Nao's network when you plug in the cable, you will nee to give your ethernet port an IP address with the same subnet as Nao's. Make the first 3 numbers the same as Nao's, and the last number different.

On windows:
<ol>
<li> control panel</li>
<li> network and sharing center</li>
<li> change adapter settings</li>
<li> pick an interface</li>
<li> properties</li>
<li> internet protocol v4</li>
<li> properties</li>
<li> enter ip address and netmask</li>
</ol>

On Linux:
<ol>
<li> open terminal</li>
<li> find out your interface name:</li>

    ifconfig

<li> give that interface an ip address:</li>
       
    sudo ifconfig <interface name> <ip address> netmask 255.255.255.0
    
</ol>

___

How to Download Choregraphe:
<ol>
<li> In order to download Choregraphe, Nao has to be registered.</li>
<li> Go to http://doc.aldebaran.com/2-4/dev/community_software.html#retrieving-software</li>
<li> Follow the directions to download the program.</li>
<li> When you're able to open it, it will ask for an activation code.</li>
    -copy and paste the activation code: 654e-4564-153c-6518-2f44-7562-206e-4c60-5f47-5f45

<li> After you type in the activation code, you will be on the home page of the Choregraphe application. </li>
</ol>

___

How to do a Basic Choregraphe project:
<ol>
<li> Open your choregraphe application</li>
<li> Click "New Project"</li>
<li> There should be a virtual robot in the bottom right corner. If not:</li>

   -click connection in the top left corner
        
   -click connect to
        
   -click the desktop robot
        
   -if that doesn't work, try exiting out of choregraphe and try again
        
<li> On the left side of the screen, there should be a box with libraries of actions. If not:</li>

   -click view in the top left corner
        
   -click the first option: "box libraries"
        
<li> Click and drag the say option to the middle of the screen</li>
<li> Double click the "say" box, it will bring you to a localized text box</li>
<li> Here, you can change the language, and pick what you want him to say</li>
<li> Type "Hello humans!" into the localized text box</li>
<li> Click root to go back to the main project</li>
<li> Click the small box in the left hand corner with the black arrow</li>
<li> Drag the "noodle" from the first small box to the small box with the black arrow on the "say" box</li>
<li> To run your program, click the green arrow at the top</li>

   -If nothing happens, don't worry. The virtual robot will not talk through your speakers. To make sure it's working, open the dialog box
<li> To open the dialog box, click view, then click the dialog box option</li>

<li> Try running your program again, "Hello humans!" will pop up in the dialog box*</li>

   -when you connect the real robot to your computer, he will say it out loud
    
<li> Don't forget to save your project. Click file, then save project as...</li>
</ol>

<img src="pics/hello.png" align="middle"/>
___

Useful links

[Robo-phil youtube channel](https://www.youtube.com/user/robotphilip)

[How to package an application](http://bx.psu.edu/~thanh/naoqi/software/choregraphe/objects/application.html)

___

How to Make a Project (with multiple parts):

How to Upload Projects onto Robot:
