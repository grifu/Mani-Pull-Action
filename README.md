# [maniPULLaction](http://www.virtualmarionette.grifu.com)

Mani.Pull.Action (MAN) v.1 (developed in March 2015, public released in March 2016)

## Digital Hand Puppetry

ManiPullAction is a digital hand puppetry prototype for a research project called Virtual Marionette. It was developed in March 2015 to evaluate the hand dexterity with the Leapmotion device to manipulate digital puppets in real-time. 
I propose an ergonomic mapping model to take advantage of the the full hand dexterity for expressive performance animation.

You can try the model and contribute with your evaluation by recording the 12 tests that are available. 8 tests with the puppet Luduvica and 4 tests with Cardboard boy puppet. If agree in making this test, just write a name in the label and start by pressing the “1” key or the “>” button. After the first test you can switch to the next by pressing the “>” button or the numeric keys “2”, “3”, and so on until the “8”. Then, you can jump to the next puppet by pressing the “2” button or the “Shift-F2” key. There are more 4 tests with this puppet that can be accessed with the “1”,”2”,”3”,”4” or using the “>” button. After finishing all tests you can send all the files that were saved to “virtual.marionette@grifu.com”. You can find or reproduce the file by pressing “browse”. The files are text files and motion capture binary files.

This prototype presents 4 distinct puppets with different interaction approaches that you can experiment by pressing 1,2,3,4 buttons. It also presents live camera switching and lighting control through remote OSC in port “7000” by using applications such as TouchOSC (try the“simple” preset)
.Switch between the 4 cameras with the messages “/2/push1” .. to “/2/push4”, to manipulate the lights use “/1/fader1” to “/1/fader4”, to focus and defocus the camera 3 on the Cardboard and Mr. Brown scenes use the “/1/fader5”. You can also navigate through scenes with the addresses “/2/push13” to “2/push16”.


Developed by Grifu in 2015 for the Digital Media PhD at FEUP (Austin | Portugal) supported by FCT

It requires the Leapmotion device. 

## Demo video
https://vimeo.com/grifu/manipullaction


## License

    Copyright 2012-2016 Luís Leite

                    GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <http://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

                            Preamble

  The GNU General Public License is a free, copyleft license for
software and other kinds of works.



## Support forum
![Forum](http://www.grifu.com/vmforum)
![mail](virtual.marionette@grifu.com)

## Researh project
![Support](http://www.virtualmarionette.grifu.com)



## Developed with
Unity with Leapmotion SDK and Stringless plugin

