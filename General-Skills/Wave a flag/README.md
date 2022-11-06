## 🌊 Wave a flag
This flag was as easy as the first one...

The challenge description is :

```
Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...
```

But of course, I didn't read it and go ahead analysing the file.

I used the good old `file` command to get informations about the file:

```
$ file ./warm
./warm: ELF 64-bit LSB pie executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, for GNU/Linux 3.2.0, BuildID[sha1]=3181a501366281ab5eba1c41e54a1f40800e3966, with debug_info, not stripped
```

As we see, this is an `ELF` file so an executable. 

I used the `strings` command to read through the file and maybe understand how this executable works:

*See the `strings-command.png` image in the current directory.*

And here's the flag !