# MatixOS-Kernel

On Linux 

    - make sure gcc, g++, make and mercurial are installed On OSX

    - make sure mercurial and XCode with command line tools are 
      installed

 1. Open a terminal, and move to the tools folder and extract all
    compressed files.
 
 2. Run the following command. This will take at least 10-15 minutes
    to complete: 
   
    ./get_tool_sources && ./build_binutils && ./build_gcc 

 3. Move to the src folder (parent of the tools folder) 

 4. Run: make

 5. Install qemu (either via HomeBrew on OS X or via the package manager in Linux) 

 6. You can then run the OS mirco kernel with sh -x run.sh 
