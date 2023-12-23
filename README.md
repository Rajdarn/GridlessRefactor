# GridlessRefactor
A simple plugin that fixes (mostly) the Godot export from GridlessDB to work with Godot 4

# How to install and use:
Download gridlessrefactor.zip and unzip into your Godot_project/addons folder. Create an addons folder if you don't have one.

In Godot, go to Project->Project Settings->Plugins and enable the plugin

A new tab will appear

![1](https://github.com/Rajdarn/GridlessRefactor/assets/71663616/bd416221-f6e4-486b-b819-7ecd9a8cc35e)

Drag the .gd-file you got from GridlessDB (should be located in Database/classes) onto the text field that reads "Drag the Gridless class..."

Press "Refactor"

Godot will need to reaload the file before you can see any changes so on Windows you can just press the taskbar and click back into Godot or just ALT+TAB and back.

You should be prompted with a window that asks if you want to reload the file. Click "Reload".

Open the .gd file and make sure there are no errors. Any errors can be fixed manually.

When you double click any .tres file in the objects folder the output might read "Attempt to open script 'res://Database/classes/Category.gd' resulted in error 'File not found'."
If so you can just move your Database folder to the project root (res://) and back into the gridlessDB folder and that should resolve it. You'll have to do this for each time you export the database from GridlessDB.

That should be it. Hopefully it saves a bit of time.

# Disclaimer:
I'm just a dumb hobbyist and hacked this togeather so use it at your own risk.
If you're a smart person, please feel free to make a better version.
By making this and putting it up on github I am in no way obligated to continue working on making this better or adding any features so don't expect anything more than this.
