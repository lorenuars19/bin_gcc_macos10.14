# Intallation

Clone this git in your ~/bin folder

the executable name is `g++_` it is actually a symlink

# Infos

Compiled with

```sh
../configure --prefix=$HOME/bin/ \
--enable-checking=release \
--enable-languages=c,c++ \
--disable-multilib \
--with-sysroot=/Library/Developer/CommandLineTools/SDKs/MacOSX.sdk \
--program-suffix=-11.2 \
```
