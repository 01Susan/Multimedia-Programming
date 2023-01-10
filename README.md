# Graphics library setup 

## Quick setup

```bash
git clone https://github.com/ullaskunder3/graphics.h-project-template.git
```

Detail setup can be found on my other repo [solution-to-graphics.h](https://github.com/ullaskunder3/Solution-to-graphics.h)

## My directory look like

```cmd
  D:.
├───.vscode
└───Home
    ├───build
    └───src
```

- Just `Ctrl+Shift+B` to run the build task you will get the executable file in build folder

## !mportant

- Folder `src` contains source code

- Folder `build` where compiler generate .exe

- .vscode contains c_cpp_properties.json and task require modification according to your environment and types compiler


# Copy [`MinGW`](https://sourceforge.net/projects/mingw/) folder to MINGW install location might be `C:\MINGW`
- ## Put your code in `Home/src`
- ## Use `Ctrl+Shift+B` to build.
    - ### Output will be put in `Home/build`
    - ### Open the exe files in `Home/build` to run the program

`Note: call the initgraph function only after taking in all of the required values`

[Reference for environment](https://github.com/ullaskunder3/Solution-to-graphics.h)