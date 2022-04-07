# Intallation

Clone this git in your ~/bin folder

the executable name is `g++_` which is actually a symlink

# Usage 
Add `-fsanitize=leak` to your compilation flags
additionally you can force the activation of ASAN
<br>
```sh
export ASAN_OPTIONS=detect_leaks=1
```
[more info on LeakSanitizer](https://github.com/google/sanitizers/wiki/AddressSanitizerLeakSanitizer)

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
