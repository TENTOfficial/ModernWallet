# ModernWallet

### Install dependencies

On Ubuntu systems:

```
$ sudo apt-get install \
      build-essential pkg-config libc6-dev m4 g++-multilib \
      autoconf libtool ncurses-dev unzip git python python-zmq \
      zlib1g-dev wget bsdmainutils automake curl
```

On Mac systems:

```
brew tap discoteq/discoteq; brew install flock
brew install autoconf autogen automake
brew install gcc5
brew install binutils
brew install protobuf
brew install coreutils
brew install wget llvm
```

### Check GCC version

gcc/g++ 4.9 or later is required. SnowGem has been successfully built using gcc/g++ versions 4.9 to 7.x inclusive. Use ```g++ --version``` to check which version you have.

On Ubuntu Trusty, if your version is too old then you can install gcc/g++ 4.9 as follows:

```
$ sudo add-apt-repository ppa:ubuntu-toolchain-r/test
$ sudo apt-get update
$ sudo apt-get install g++-4.9
```
