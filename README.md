# Blender 2.9x Texture Switch Node

Hello there!
This is my first Github upload.  

This setup is a very simple 10-way-switch that makes working with many textures on the same object very easy.
I know that Blender can read image sequences in texture slots, but from what I know only if they are named sequential like 001, 002, 003. In my day-to-day these things get more complicated and instead of creating lots of duplicates that I can't remember the name of, I can keep the original source files untouched.

How-to for beginners:
You can add this node setup to Blender via the File/F4 > Append...", double click the provided *.blend file and from there, go to "NodeTree" and choose the TextureSwitch. 
Then go to your material you want to use it with and press Shift+A -> Group > TextureSwitch_v1

If you animate the switch parameter be sure to set the animation to linear interpolation, otherwise you might get floating numbers. You want integers, full numbers like 1, 2, 3 up to 10.

![Add Node Setup](/images/textureswitch.png)

![Add Node Setup](/images/textureswitch2.png)

The approach is based on this Youtube Video from a while ago. Thank you "A" for the tip!
https://www.youtube.com/watch?v=0glf-acMvcw
