# Obedient Cat from picoCTF
## Solved on Kali VM

In this challenge, you are only given a file and you are told the flag is in plain sight. However, the file is just "flag" with no file extension. 

To solve this challenge, I opened my terminal and went to my Downloads directory where the file got downloaded to. I used the `file` command to see what kind of file flag was.
```
file flag
```

The output was as follows:
```
flag: ASCII text
```

From this I learned that truly the flag is in plain sight and the file just didn't have an extension. I then ran this command which printed out the flag.
```
cat flag
```

*All credit for this challenge goes to picoCTF. I did not create it or the included "flag" file. This is simply my solution to the problem and the "flag" file is included for reference.*
