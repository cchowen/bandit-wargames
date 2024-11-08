# Level 1

Now that we have our password, we can connect to the bandit1 VM and keep going. We log in using the same host and port as before, only we're asking for the bandit1 VM rather than bandit0, and we need to use the new password we just found.

Once we've done that, our task is to retrieve the password to level 2 from a file called **-** in the home directory.

We can't simply use previous commands to examine the file as we did in the last level, because `nano -` and `vim -` instead start reading input from the keyboard. 

We can get around this by either redirecting **cat** using the `<` operator, or by specifying the full path of the filename rather than the relative path:

`cat < -` works, as does `cat ./-`

Either of these commands gives us our new password, which is 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
