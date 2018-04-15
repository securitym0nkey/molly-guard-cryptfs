# molly-guard-cryptfs

This is a plugin for molly-quard. It ensures that you are able to boot a system with an encrypted rootfs. 

With this plugin you have need to prove that
  1. You have a working access to a local tty.
  2. You know the passphrase for the crypted device.

## Requirements
  - Python3
  - molly-guard

## Install
Just place __20-crypt-rootfs__ into __/etc/molly-guard/run.d/__ and make it executable.
