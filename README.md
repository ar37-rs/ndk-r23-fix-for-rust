Extract the gcc folder inside android-ndk-r23-gcc-fix.rar file, and then put it into:

$ANDROID_SDK_ROOT/ndk/23.1.7779620/toolchains/llvm/prebuilt/linux-x86_64/lib/*here

note:
- every "libgcc.a" inside .rar file taken from earlier NDK version (r21d)
- tested on linux x86_64 using the latest rust stable toolchain.
