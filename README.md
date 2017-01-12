# basicRAT

This is a boilerplate Python RAT (Remote Access Trojan). I created this to maintain a bare-bones, clean design Python RAT with only essential features. My goal is to use basicRAT as a starting point to create other RATs that use various common-place protocols for C2.

**Disclaimer: This RAT is for research purposes only, and should only be used on authorized systems. Accessing a computer system or network without authorization or explicit permission is illegal.**

## Features
* Cross-platform
* Reverse Shell
* AES CBC Encrypted C2

## Notes
* The ELF was created using [PyInstaller](http://www.pyinstaller.org/).
* Key was generated with `binascii.hexlify(os.urandom(16))`

## Other open-source Python RATs for Reference
* [ahhh/Reverse_DNS_Shell](https://github.com/ahhh/Reverse_DNS_Shell)
* [sweetsoftware/Ares](https://github.com/sweetsoftware/Ares)
