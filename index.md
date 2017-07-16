### [CAWA-GPGPUSim](https://github.com/dmjoshyy/gpgpusim-cacp) 

This project, implemented in C++, showcases the [CAWA](https://pdfs.semanticscholar.org/0ca2/b92a4f992b35683c7fffcd49b4c883772a29.pdf)(Criticality Aware Warp Accelerator) scheme on GPGPU-Sim. In order to implement CAWA, an accurate criticality predictor was built. Using the determined criticality, warp scheduling and cache prioritizing was done. I primarily worked on cache partitoning, which meant ensuring that critical cache requests were treated to be of high priority. This was the biggest codebase I have worked on.

Main files: [CACP.cc](https://github.com/dmjoshyy/gpgpusim-cacp/blob/master/src/gpgpu-sim/CACP.cc)
### [In-Memory File System](https://github.com/dmjoshyy/mydisk) 

This project, implemented in C++, involved constructing an in-memory file system using a FUSE interface. FUSE allows for custom callbacks for linux system calls, which are used to modify the in memory file system. The File System was stress tested using postmark. The file system supported regular linux commands like cd, mkdir, pwd, ls, rm, rmdir etc. Also supported saving/loading images of the file system. 

Main files: [helloFS.cpp](https://github.com/dmjoshyy/mydisk/blob/extra_try/helloFS.cpp), [structures.cpp](https://github.com/dmjoshyy/mydisk/blob/extra_try/structures.cpp)
### [Thread Library](https://github.com/dmjoshyy/mythread)

This project, implemented in C, involved designing a thread library. The library supports basic thread functions such as Join, JoinAll, Yield and Semaphores. Thread switching was done through the inbuilt uncontext.h library.

Main files: [libtest.c](https://github.com/dmjoshyy/mythread/blob/master/libtest.c)

### [Microshell](https://github.com/dmjoshyy/ush)

This project, implemented in C, involved designing a simple shell that supported basic linux commands like cd, pwd, echo, logout and so on. Allows for redirecting output and input as well as piping multiple commands together. Also supported a .rc configuration file and kill signals.

Main files: [mycode.c](https://github.com/dmjoshyy/ush/blob/submit/mycode.c)


### [Cernal](https://github.com/dmjoshyy/cernal)
A simple Android App that scrubs CERN's RSS feed and generates a news feed. Fairly basic, but this is the first project where I learned to use APIs and parse XML. 


