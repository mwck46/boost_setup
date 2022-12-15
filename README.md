# Boost Setup Instructions

1) Set up boost path in Visual Studio for Windows

Path for hpp files  
Right click on your c++ project -> Properties -> Select "All configurations" and "All Platforms" -> C/C++ -> Additional Include Directories  
```
$(SolutionDir)\..\boost_1_80_0 
```

Path for library  
Right click on your c++ project -> Properties -> Select "All configurations" and "All Platforms" -> Linker -> General -> Additional Library Directories  
```
$(SolutionDir)\..\boost_1_80_0\stage\lib
```

