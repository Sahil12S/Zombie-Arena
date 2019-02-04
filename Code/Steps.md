# Starting the project
1. Open project in Visual Studio
2. In project properties, add include directories in C++ (path of _SFML/include_).  
3. Add path of _SFML/lib_ for Linker->general.  
4. In Debug configuration -> Linker -> Input add "_sfml-graphics-d.lib;sfml-window-d.lib;sfml-system-d.lib;sfml-network-d.lib;sfml-audio-d.lib;_".  
5. Do _Ctrl + F5_ to run the project.  