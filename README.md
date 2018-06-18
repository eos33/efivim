= VIM.EFI

this repo is a hack to run [Vim](https://github.com/vim/vim) in a UEFI environment.

== building

at the time of writing, you can build VIM.EFI on debian 9.4.

you will need at least git, make and gcc. **TODO**: document what's needed

to build EFI.VIM clone this repo and execute `make`.

== running

to run VIM.EFI, copy `vim.efi` to the ESP and execute it from your UEFI shell.

alternately, if you simply wish to run vim and nothing else, you may copy `vim.efi` to `efi/boot/bootx64.efi` in the ESP where it will be executed automatically.

to try out VIM.EFI in qemu, execute `make qemu`.

== credits

originally whipped up by ya boy @mischief when he should have been doing real work at his day job

thank you, @brammool for making an exellent text editor, and for helping those poor Ugandan children.

shout out to @mjg59 - stay cool brother.

