Requirements:
  1. Github account : Create on here (https://github.com/login)
  2. Ergo18 keyboard & USB type C
  3. Computer and internet access

This is a quick little guide for those of you who wish to change or add things to your keymap.   This guide will work for all the keyboards running ZMK.  I have crap grammar so bear with me :D

Go to my GitHub repo https://github.com/Opids14/zmk-config-ergo18 and fork it 



 Go to [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/). This will be the graphical user interface used to modify the base keymap. 

    - Log in with your GitHub account and authorize if needed.

    - Select the option "Only select repositories."

    - Click the drop-down "Select repositories" and search for the repository you forked from my GitHub: `zmk-config-corne`.

    - Click "Install."  


This will reload and display a nice GUI where you can start editing your keymap as desired. There are many settings to explore here

After making changes to the keymap, click "Save" and then "Commit."  

Go back to your GitHub repository and navigate to the "Actions" tab, where you'll see another workflow automatically running. Wait for it to finish. As long as it turns green, all changes have been accepted


Click on the new workflow once it finishes running, then download the firmware and extract the file

Set your keeyboard to bootloader by presing the lower right key and top left 
