# qc-cpp
C++ toolbox for quantum computation

## Getting Started

### Prerequisites
* GNU gcc compiler
* clang
* GNU g77 compiler
* [tclap][tclap]
* [IT++][IT++]
* [fftw][fftw]
* [[doxygen][[doxygen]
* GNU Make


## Ubuntu Build Guide
To install the dependencies, run the following commands.

```bash
sudo apt update
```

GNU gcc compiler

```bash
sudo apt install g++ clang ibc++-helpers pentium-builder
```
GNU g77 compiler

```bash
sudo apt install gfortran
```

IT++

```bash
sudo apt install libblas-dev librtlsdr-dev libncurses5-dev libitpp-dev -y
```

Doxygen

```bash
sudo apt install doxygen graphviz
```

[tclap]: https://sourceforge.net/projects/tclap/
[IT++]: https://sourceforge.net/projects/itpp/
[fftw]: http://fftw.org/
[doxygen]: http://www.doxygen.org/
