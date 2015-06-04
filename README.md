These instructions will allow you to easily checkout the latest source of [LLVM](http://llvm.org/), including the [clang compiler](http://clang.llvm.org/) and various tools.

# Requirements

To checkout the LLVM source tree, get the repo tool: https://source.android.com/source/downloading.html#installing-repo

# Initialize source tree

For the initial checkout of the source tree, perform the following steps:

```
# mkdir llvm
# cd llvm
# repo init -u https://github.com/markun/llvm-repo.git
# repo sync
```

# Update source tree

To update the source tree, enter the the directory and do:

```
# repo sync
```

# Building LLVM

To build LLVM, follow the instructions at: http://llvm.org/docs/CMake.html
