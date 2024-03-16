To **build** example:

'''
mkdir ../Step5_build
cd ../Step5_build
cmake ../Step5 -DUSE_MYMATH=OFF
cmake --install . --config Debug --prefix "D:/cpp_solutions/Step5Project/install"
'''

In case you want to run unit tests navigate to build directory and **run**:
```
ctest -C Debug -VV
```