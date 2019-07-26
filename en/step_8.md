## Export your tidy

In this step, you will export your model so that it can be printed. There are a lot of different types of 3D printer, but most of them will accept `.stl` files or `.gcode` files. You will probably find it easiest to export the model as an `.stl` file and then use an external program to convert this into a `.gcode` file.

--- task ---
Select the body in the **Model** tab. Click on **File**, then click on **Export**. In the **Files of type** drop-down menu, select the `.stl` option. Give your model a name, then click on **Save**.

![export](images/export.png)
--- /task ---

If your 3D printer requires `.gcode` files, then you can use an external application to convert the `.stl` file. The instructions below are for [Cura](https://ultimaker.com/en/products/ultimaker-cura-software).

--- task ---
Open Cura from your **Applications** menu.

![Cura1](images/cura1.png)
--- /task ---

--- task ---
Go to the **File** menu and open your `upper.stl` and `lower.stl` files.
--- /task ---

--- task ---
Position the two models side by side and rotate them so that they lie flat on the bed.

![Cura3](images/cura3.png)
--- /task ---

--- task ---
Use the settings on the right-hand side to choose your **material**, **profile**, **infill**, and any **support** you might need.
Here, the material is PLA, the profile is set to standard detail and a 20% infill has been chosen.

![Cura3](images/cura4.png)

Once you are happy with the settings for your 3D printer, use the menu on the left-hand side to save your `.gcode` file.
--- /task ---
