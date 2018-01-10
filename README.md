# openjdk_interpreter_performance_test
source: https://community.oracle.com/blogs/simonis

DaCapo performance test suite with both interpreters in interpreter only mode (-Xint) and in mixed mode (-Xmixed) together with the C2 server JIT compiler. The tests have been executed with a 32-bit VM on Linux/x86 and with a 32- and a 64-bit VM on Solaris/SPARC. The results can be seen in the following tables.

## Table 1 (-Xint)
![alt text](data:https://user-images.githubusercontent.com/33415010/34774613-f1541a52-f64a-11e7-943a-f57d12797612.png)


In interpreter mode (-Xint) the performance of the C++ interpreter varies between 35 and 50 percent of the performance of the template interpreter. In mixed mode (-Xmixed) a VM that runs with the C++ interpreter reaches from 45 up to 90 percent of the performance of a VM that runs with the template interpreter.


 
 
