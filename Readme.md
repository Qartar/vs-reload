# Reproduction Steps

1. Clone this repository
2. Open `vs-reload.sln` in Visual Studio 2017
3. Open `a.cpp`, `b.cpp` (source files) and `c.cpp` (external file) into tabs on the main window
4. Checkout the previous commit using git (e.g. `git checkout HEAD~1`)
5. Return to Visual Studio, when prompted to reload the solution hit "Reload All"
6. Note that the tabs for `b.cpp` (not part of the solution in the previous commit) and `c.cpp` have been closed
