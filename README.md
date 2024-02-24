# Boost Setup Instructions

## Windows

Include .hpp  
1) Project Properties -> "All configurations" and "All Platforms" -> C/C++ -> Additional Include Directories  
```
$(SolutionDir)\..\boost_1_80_0 
```

Include build lib  
1) Open Developer Command Prompt for VS 2022
   ```
   bootstrap
   .\b2
   ```
2) Project Properties -> "All configurations" and "All Platforms" -> Linker -> General -> Additional Library Directories
   ```
   $(SolutionDir)\..\boost_1_80_0\stage\lib
   ```

