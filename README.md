# 🌱 Zlib Scaffold

A minimal zlib project template

## 🦄 Usage

Simply click the button below to get started:

[![Use this template](https://img.shields.io/badge/use%20this%20template-brightgreen.svg?longCache=true&style=for-the-badge)](https://github.com/xmake-examples/zlib-scaffold/generate)

## 🔨 Development

###  📋 Requirements

To setup and use the project you will need to have the following tools installed:
 - [Xmake](https://xmake.io/)

###  ⬇️ Installation

Clone the repository

```bash
$ git clone https://github.com/xmake-examples/zlib-scaffold.git
```

Change the working directory to the newly cloned repository:

```bash
$ cd zlib-scaffold
```

Run xmake to install the dependencies & build the project:

```bash
$ xmake
note: install or modify (m) these packages (pass -y to skip confirm)?
in xmake-repo:
  -> zlib v1.2.12
please input: y (y/n/m)

  => download https://github.com/madler/zlib/archive/v1.2.12.tar.gz .. ok
  => install zlib v1.2.12 .. ok
[ 25%]: cache compiling.release src/main.c
[ 50%]: linking.release zlib-scaffold
[100%]: build ok!
```

Run the project after it has been built:

```bash
$ xmake run
zlib version 1.2.12 = 0x12c0, compile flags = 0xa9
uncompress(): hello, hello!
gzread(): hello, hello!
gzgets() after gzseek:  hello!
inflate(): hello, hello!
large_inflate(): OK
after inflateSync(): hello, hello!
inflate with dictionary: hello, hello!
```

![](/res/example.png)
