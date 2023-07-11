# Obfuscator LLVM (OLLVM)

This repository is a fork of [obfuscator-llvm/obfuscator](https://github.com/obfuscator-llvm/obfuscator) with patches and updates since the original project is no longer maintained. For more information about the original project, please visit the original project's [wiki](https://github.com/obfuscator-llvm/obfuscator/wiki)! Currently, this repository patches the [LLVM-4.0](https://github.com/obfuscator-llvm/obfuscator/tree/llvm-4.0) version of the project.

## Installation
The following are slightly modified installation instructions from the original project to build this repository.

```bash
$ git clone https://github.com/bliutech/obfuscator.git
$ mkdir build
$ cd build
$ cmake -DCMAKE_BUILD_TYPE=Release -DLLVM_INCLUDE_TESTS=OFF -DLLVM_PARALLEL_LINK_JOBS=1 ../obfuscator/CMakeLists.txt
$ make -j7
```

## Citation
You can cite Obfuscator-LLVM using the following Bibtex entry:

```
@INPROCEEDINGS{ieeespro2015-JunodRWM,
  author={Pascal Junod and Julien Rinaldini and Johan Wehrli and Julie Michielin},
  booktitle={Proceedings of the {IEEE/ACM} 1st International Workshop on Software Protection, {SPRO'15}, Firenze, Italy, May 19th, 2015},
  editor = {Brecht Wyseur},
  publisher = {IEEE},
  title={Obfuscator-{LLVM} -- Software Protection for the Masses},
  year={2015},
  pages={3--9},
  doi={10.1109/SPRO.2015.10},
}
```

## LLVM Information
Contents of `README.txt` from the original LLVM project.

```
Low Level Virtual Machine (LLVM)
================================

This directory and its subdirectories contain source code for LLVM,
a toolkit for the construction of highly optimized compilers,
optimizers, and runtime environments.

LLVM is open source software. You may freely distribute it under the terms of
the license agreement found in LICENSE.txt.

Please see the documentation provided in docs/ for further
assistance with LLVM, and in particular docs/GettingStarted.rst for getting
started with LLVM and docs/README.txt for an overview of LLVM's
documentation setup.

If you are writing a package for LLVM, see docs/Packaging.rst for our
suggestions.
```
