# mingw-dist

This builds MinGW and strips everything to the bare essentials to work as a compiler for lde's needs.

Used https://github.com/niXman/mingw-builds for reference.

## Note

This has to be distributed as a .7z file which is not supported by Windows OOTB.

This is because using anything but lzma leads to significantly larger file sizes.

## Supported Platforms

| Platform    | Architecture    | Size  | Download                                                                                               |
| ----------- | --------------- | ----- | ------------------------------------------------------------------------------------------------------ |
| **Windows** | x86-64          | ~28mB | [✅ Download](https://github.com/lde-org/mingw-dist/releases/latest/download/mingw-windows-x86-64.7z)  |
| **Windows** | aarch64 (ARM64) | N/A   | [✅ Download](https://github.com/lde-org/mingw-dist/releases/latest/download/mingw-windows-aarch64.7z) |
