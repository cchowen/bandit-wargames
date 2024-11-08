# level 3

In level 3, our task is to find the password in a file in the **inhere** directory. Complicating things a bit is the fact that this file is hidden. If we use `cd` to hop into the **inhere** folder and `ls` to list the files, it looks like there's nothing here!

Looking at the manual for `ls`, it looks like the `-a` or `-all` flag ignores hidden files, so let's try that. Running `ls -a` shows two hidden directories named `.` and `..` respectively, and a hidden file named `...Hiding-From-You`. Now that we have our filename, we can read its contents as normal to retrieve our password: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
