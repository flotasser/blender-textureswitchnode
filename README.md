# Blender 2.9x Texture Switch Node

Hello there!
This is my first Github upload.  

Blender usually makes it not too easy to change textures in slots. This setup is a very simple 10-way-switch that makes working with many switching textures on the same object very easy.
I know that Blender can read image sequences in texture slots, but from what I know only if they are named sequential like 001, 002, 003. In my day to day these things get more complicated and instead of creating lots of duplicated that I can't remember the name of, I can keep the original source files untouched.

You can add this node setup to Blender via the File/F4 > Append...", double click the provided *.blend file and from there, go to "NodeTree" and choose the TextureSwitch. 
Then go to your material you want to use it with and press Shift+A -> Group > TextureSwitch_v1

Put in your Image Texture, Procedural Nodes or whatever you like in the slot you want and then you can for example animate the "Switch" to be 1 at frame 1 and 10 at frame 10. Be sure to check that the frames are set up correctly to linear. 
This is a workaround for me to be able to use different bump maps, normal maps, height maps and automate the process. At work, I render products and packaging and need to quickly iterate. But you can do many other things.

![Add Node Setup](/images/textureswitch.png)

![Add Node Setup](/images/textureswitch2.png)

The approach is based on this Youtube Video from a while ago. https://www.youtube.com/watch?v=0glf-acMvcw

