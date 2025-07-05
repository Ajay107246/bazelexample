# First example bazel with C++ project

## Command to build this project:
1. Navigate to bazelex/
2. Exeucte bazel build commad: bazel build //src:hello-world
```
bazel build //src:hello-world 
INFO: Analyzed target //src:hello-world (68 packages loaded, 476 targets configured).
INFO: Found 1 target...
Target //src:hello-world up-to-date:
  bazel-bin/src/hello-world.exe
INFO: Elapsed time: 14.686s, Critical Path: 0.72s
INFO: 6 processes: 4 internal, 2 local.                                                                             
INFO: Build completed successfully, 6 total actions
```
3. Executre bazel run  commad: bazel run //src:hello-world

```
bazel run //src:hello-world  
INFO: Analyzed target //src:hello-world (32 packages loaded, 158 targets configured).
INFO: Found 1 target...
Target //src:hello-world up-to-date:
  bazel-bin/src/hello-world.exe                                                                                     
INFO: Elapsed time: 1.017s, Critical Path: 0.04s
INFO: 1 process: 1 internal.
INFO: Build completed successfully, 1 total action                                                                  
INFO: Running command line: bazel-bin/src/hello-world.exe
Hello from Bazel + C++!
```
4. Execute clean command: bazel clean
```
bazel clean
INFO: Starting clean.
```
### Bazel source: 
https://github.com/bazelbuild/bazel/tree/master

NOTE: Make sure you have installed bazel in correct way.