# Quake in Visual Studio 2019 

Change the configuration to x86 (Win32 mode) before running.

Change the working directory in Visual Studio 2019 to point to your Quake directory (Project->Properties, Configuration Properties->Debugging->Working Directory)

In quakedef.h, define GLQUAKE to build the OpenGL version, otherwise it will build software/Winquake.

Winquake/software:
- Start the game with -startwindowed

GLQuake:
- Start the game with -no8bit if the textures don't work, e.g. -width 800 -height 600 -bpp 32 -window -no8bit
- r_flashblend 0 to turn off the silly yellow circles when people shoot
