# OpenCV starter

**make sure that you have installed all pkg you need and correct environment settings**

## To use this example code, you only have to follow the steps below.

remember to install *libgtk2.0-dev* before *cmake .* The command is as bellow  

    sudo apt install libgtk2.0-dev  
then do 

    `cmake . && make`

## To compile a .cpp file you code

1. Create a .cpp file, finish your code.
2. Use the terminal in vscode or create a new terminal in the same place where you put your code. Use the command below to create a Cmake generating file.  

    `cat > CMakeLists.txt`

3.  Setup your *CMakeLists* file. In this session, you'd have to link the libs you need and define the excutable file, which you could learn in this website:

    [Cmake tutorial](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)

4. Open the terminal, start building your code. Follow steps as blow:

    `cmake .`

    `make`
5. After compiling finished, run the excutable file generated automatically by camke, using:

    `./"name of your excutable file"  parameters`