#Build Instruction and Additional notes

Overview of HW1:
1) Maze Generation
2) BFS Implemenation to solve Maze
3) Animation visualizations to help users see what cells were explored versus which ones contribute to the final path.
4) Adjustable animation speed with keys.
5) Dynamic Window resizing
6) Command line inputs for maze size arguments
7) We are guaranteed to find a path from green to red (start to finish).


Build Instructions through PACE-ICE (using CMake and SFML 3):
1) Start an interactive session on PACE-ICE.
2) Go to the project folder.
3) Create the build directory. (mkdir build)
4) Navigate to the build directory. (cd build)
5) In the build folder run: cmake ../ -DCMAKE_BUILD_TYPE=Debug
6) Then run cmake --build . -j8
7) The executable is in output/bin so run: cd ../output/bin followed by ./hw1

Build Instructions on Mac:
1) brew install sfml (to install smfl through homebrew).
2) Then create the build directory using: mkdir build
3) Cd into that directory: cd build
4) Then: cmake ..
5) cmake --build .
6) cd ../output/bin
7) Then run it using: ./hw1
8) Alternatively, the program accepts maze dimensions throught the form ./hw1 <width> <height>.
