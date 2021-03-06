Chapter 2.4.4: PCManFM-Qt
=========================

Description
------------
PCManFM-Qt (PCMan File Manager) is a file manager application ported to Qt after the original developed by Hong Jen Yee from Taiwan which is meant to be a replacement for Nautilus, Konqueror and Thunar. 

Features:
 - tabs
 - bookmarks
 - places with removable media 
 - Ability to eject removable media and the ability to mount other filesystesms internally.

Useage
------
Along the top to create a new tab in pcmanfm-qt you can use the button with a file and a plus on it to open a new tab or press control +t. The left pointing arrow button is a back button while the right pointing arrow button moves you forward in the directories that you have moved in the file manager. The button for the arrow pointing upward is to go up one level in the directory tree to the so called parent directory.

If you single click on a file you will select it. If you double click on it you will open it in the  default program to open that file. If you right click on a file you can select  which program to open a file with if you have multiple programs to open it. If you want to selct multiple files you can hold down control and select the files. To copy files select the file right click copy or press control +c. To cut files select them right click cut and or press control + x. After copying or cutting a file you can paste them with right click paste or press control +v.  

To connect to a remote server such as a NAS go to the go menu -> Connect to server and authenticate to your remote storage. If you want to plug in removeable storage you can open the storage on the left with devices.  This also happens other internal filesystems on your computer. To eject removeable media press the button on the left with a circled up arrow to eject.   



Screenshot
----------
.. image:: pcmanfm-qt.png 


Version
-------
Lubuntu currently ships with 0.13.0 of pcmfanfm-qt. 

How to Launch
-------------
To open PCManFM in your current directory (in terminal), execute 

.. code::

   pcmanfm-qt

Feel free to append [lxqt-sudo] to run PCManFM-Qt as root.

You can also go to the Applications Menu > Accessories > PCManFM-Qt File Manager.
