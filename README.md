# MakeCplusplus
Assuming make is installed, this makefile automatically compile C++ code under linux. Simply enter bash command in your C++ Project directory:
```bash
  make clean # remove *.o in current directory and ./include
  make      # compile *.cpp in current directory and in ./include)
```
Your executable file will be named as your project directory name (I.e. $PWD under linux)
