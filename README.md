# Szkolenie C++11/14 - Motorola #

## Ankieta

* https://forms.gle/vtr1BJyg8CNeJfu3A

## Docs

* https://infotraining.bitbucket.io/cpp-11
* https://gitpitch.com/infotraining-dev/cpp-11/develop?grs=bitbucket&p=slides_pl#/
* https://gitpitch.com/infotraining-dev/cpp-thd/develop?grs=bitbucket&p=slides_pl#/

## Maszyna wirtualna (SSH)

* link do rejestracji: https://labs.azure.com/register/rrteny9y
  - wymagania: konto Github lub Microsoft

## Toolchain

### Kompilator + CMake

* Dowolny kompilator C++ (gcc, clang, Visual C++) wspierający C++11/14

* CMake > 3.8

### [Menadżer pakietów - Vcpkg](https://github.com/microsoft/vcpkg)
  
  Instalacja vcpkg: 
  
  ```
  $cd ~
  $ git clone https://github.com/microsoft/vcpkg
  $ ./vcpkg/bootstrap-vcpkg.sh
  ```

  Dodać do pliku `.profile`:

  ```
  export VCPKG_ROOT=$HOME/vcpkg
  ```
  
  Instalacja bibliotek:

  ```
  $ ./vcpkg/vcpkg install [packages to install]
  ```

## Biblioteki

* [Catch2](https://github.com/catchorg/Catch2)

## Visual Studio Code

* [Visual Studio Code](https://code.visualstudio.com/)

### Dodatki

* C/C++
* CMakeTools
* Live Share
* Remote - SSH