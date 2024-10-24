### xmake cross compile command plugin

Easily execute xmake cross-platform compilation with a single command.

### usage

1、copy plugins to your xmake project

2、add plugin to your xmake

```lua
add_plugindirs("plugins")
target("qjs")
```

3、run

```sh
xmake xross iphoneos|linux|macosx|mingw|android
```

```sh
Command options (xross):
          platform                   target platform.
                                        iphoneos|linux|macosx|mingw|android
          arch                       target arch.
                                        iphoneos: armv7|armv7s|arm64|i386|x86_64
                                        linux: arm64|x86_64
                                        macosx: arm64|x86_64
                                        mingw: arm64|x86_64
                                        android: arm64-v8a|armeabi-v7a|x86_64   
```