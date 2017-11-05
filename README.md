# Bazel tutorial for C++
This is a sample Bazel tutorial project for C++ based on following two documents provided by Bazel official.
* [C++ and Bazel](https://docs.bazel.build/versions/master/cpp-use-cases.html)  
* [Common C++ Use Cases](https://docs.bazel.build/versions/master/cpp-use-cases.html)  

## How to use it
There are multiple directories in which contain tutorial Bazel project.  
You can move into those directories and bazel command to try bazel features.  

### For example  
``` bash
$ cd stage4
$ bazel build //main:hello-world
$ bazel-bin/main/hello-world some-file full-path-to-some-file  
$ bazel test //test:hello-test