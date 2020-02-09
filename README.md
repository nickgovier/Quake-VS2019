# Quake in Visual Studio 2019 

Change the configuration to x86 (Win32 mode) before running.

Change the working directory in Visual Studio 2019 to point to your Quake directory (Project->Properties, Configuration Properties->Debugging->Working Directory)

In quakedef.h, define GLQUAKE to build the OpenGL version, otherwise don't for software/Winquake.

Start the game with -no8bit if the textures don't work in GLQuake, e.g. -width 800 -height 600 -bpp 32 -window -no8bit
