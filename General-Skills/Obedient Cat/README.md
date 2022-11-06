## 🐈‍⬛ Obedient Cat
This flag is was as easy as opening the file.

But old habits, before opening it I used the `file` command to know more the type of file this is:

```
$ file flag
flag: ASCII text
```

To get the flag I used `strings` on the file to read the content:

```
$ strings flag
picoCTF{s4n1ty_*****************}
```

And we get the flag in the content of the file !