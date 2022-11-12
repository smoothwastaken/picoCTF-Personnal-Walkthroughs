## 🔎 Tab, Tab, Attack

First, we have to download the zipped file:
![Downloaded File]("https://github.com/smoothwastaken/picoCTF-Personnal-Walkthroughs/blob/master/General-Skills/Tab%2C%20Tab%2C%20Attack/assets/downloaded_file.png?raw=true")

Then I created a copy of the original file to play with:
![Copied File]("https://github.com/smoothwastaken/picoCTF-Personnal-Walkthroughs/blob/master/General-Skills/Tab%2C%20Tab%2C%20Attack/assets/copied_file.png?raw=true")

I unzipped the file with the `unzip` command.
![Unzip zipped file]("https://github.com/smoothwastaken/picoCTF-Personnal-Walkthroughs/blob/master/General-Skills/Tab%2C%20Tab%2C%20Attack/assets/unzip_file.png?raw=true")
What is very useful with this tool is that it logs all the process of unzipping. So here we can see that there's a folder containing another folder containing another folder and so on, until we notice a file named `fang-of-haynekhtnamet`:
![File properties]("https://github.com/smoothwastaken/picoCTF-Personnal-Walkthroughs/blob/master/General-Skills/Tab%2C%20Tab%2C%20Attack/assets/file_properties.png?raw=true")
Here's another more visual way to see what did we unzip with the `tree` command:
![tree command result]("https://github.com/smoothwastaken/picoCTF-Personnal-Walkthroughs/blob/master/General-Skills/Tab%2C%20Tab%2C%20Attack/assets/tree_unzipped_folder.png?raw=true")

Finally, using the `strings` and `grep` commands together gave me the flag inside the file !
![strings grep and flag]("https://github.com/smoothwastaken/picoCTF-Personnal-Walkthroughs/blob/master/General-Skills/Tab%2C%20Tab%2C%20Attack/assets/strings_grep_and_flag.png.png?raw=true")