# improved-Matlab-GUI
Short code to quickly generate object-oriented Matlab GUI (alternative to GUIDE).

A few things about this GUI:

1) the code is written in an object-oriented way, meaning that properties (obj.dir.project) and methods (obj.call_button1()) can be called from the obj. This means that you do not need to store variables in handles and use GUIData to update the variable handles)

2) you can access and modify any property of any element of the GUI via the obj (e.g. obj.el.button1.Color = [0 1 0])

3) click right on any element of the GUI opens the code of the callback function (which is executed when you click left on a button). The function FindCode does that.

4) the number of elements of the GUI can be modified programmatically by adding a string to the list of elements (cell variable El). No more opening GUIDE to add a button to your GUI
