# Xtensa ESP32 Toolchain for RIOT-OS

This is a precompiled Xtensa ESP32 Toolchain generated with crosstool-NG
and configured for use with RIOT-OS.

The differences to the precompiled toolchain from Espressif are:

1. It has enabled the IOs for C99 formats long long, floats, and doubles.
2. The POSIX thread support is disabled.
3. newlib is compiled with nano-malloc and nano-formatted-io
