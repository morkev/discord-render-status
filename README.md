# Discord Rendering Display Status

<img alt="GitHub all releases" src="https://img.shields.io/github/downloads/morkev/discord-render-status/total"> ![](https://img.shields.io/appveyor/build/gruntjs/grunt) <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/morkev/discord-render-status">

This Python script automatically updates your Discord status based on the Windows application you're currently running. Additionally, it includes a timer to display the elapsed time since you started using the application.

## Supported Programs

```sql
Programs currently supported:
- NX Siemens
- SOLIDWORKS
- AutoCAD
- AutoCAD Civil 3D
- Solid Edge
- Rhino
- Houdini
- Blender
- MATLAB
- Simulink
- Inventor
- Revit
- Creo
- PTC Windchill
- CATIA
- COMSOL Multiphysics
- Bentley Systems
```

## Discord Status Example

|           NX Siemens           |           Houdini           |
| :----------------------------: | :-------------------------: |
| ![NX Siemens](https://github.com/morkev/discord-render-status/assets/83437383/f060f682-c2d9-4adc-a670-c387297f2a5b) | ![Houdini](https://github.com/morkev/discord-render-status/assets/83437383/d363f57c-315f-4ef6-b938-1c049a1fa13d) |

## Setup

- Go to "Releases" and download the latest version of "RenderWindows.exe".
- That's it, you're done! Now you just have to double click on it!

## Want to Run Automatically at Startup?

- Locate the .exe file:
  - Right-click on it and select `Create shortcut`.
- Find the Startup Folder:
  - Press `Win + R` on your keyboard to open the Run dialog box.
  - Type `shell:startup` and press Enter. This will open the Startup folder.
- Place the Shortcut:
  - Drag and drop the shortcut you created into the Startup folder.

Now, every time you start Windows, the .exe file should run automatically. If you ever want to remove it from startup, simply go back to the Startup folder (shell:startup) and delete the shortcut.

## Credits

Developed by Kevin Mora.

Inspired by some of my engineering friends that use NX and CAD on a daily basis. Programmers have Discord extensions to share that they are currently coding in X language - I figured it would be cool to make something similar for rendering users.

## Support

For questions, issues, or suggestions, please refer to the "[Issues](https://github.com/morkev/discord-render-status/issues)" section. If you'd like to see a different logo/title being displayed in a certain application, or if you'd like to add a software that is not included above, please feel free to comment there.
