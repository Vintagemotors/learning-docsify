

<h1 align=center>CMake for absolute beginners (by a recent absolute beginner)</h1>

Go [here](https://makefiletutorial.com/) for advanced stuff. 


## <p style="text-align: center;">Building + installing with Makefile</p>

Go to the source folder you downloaded and extract it. Open a terminal. If the source directory already has a build folder cd to it, if not cd to the source directory and run "mkdir build" then "cd build" after that run "make" if you are on a UNIX system (like Linux or MacOS) and you want the application to be installed where your normal applications are so you can find it easily and search for it run "make install". 


## <p style="text-align: center;">Building + installing from CMakelists.txt</p>

Go to the source folder you downloaded and extract it. Open a terminal. If the source directory already has a build folder cd to it, if not cd to the source directory and run "mkdir build" then "cd build" after that run "cmake .." then run "make" if you are on a UNIX system (like Linux or MacOS) and you want the application to be installed where your normal applications are so you can find it easily and search for it run "make install". 


## Dependency errors 

Start by checking to see if the project has a list of dependencies under a building page or in the docs, if it does then install them. If it doesn't then check to see if they have a GitHub actions script under .github/workflows and if they do, see what dependencies it is installing. For windows you can install with chocolatey or another package manager, on MacOS you can use MacPorts or brew (brew will complain and often have some errors if it's not being run on the absolute latest system so I prefer MacPorts). On linux you can use your distribution's default package manager such as apt, apt=get, pacman and so on. 




