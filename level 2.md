# Level 2

Log into bandit2 as we usually do.

Our goal is to find the password from a file called **spaces in this filename** in the home directory.

The spaces in the filename present an issue for reading the filename as we usually do, since we'll read each word in the name individually and fail to find any files by those names.

We can get around this by quoting the filename in full with quotation marks. `cat "spaces in this filename"` will read the file and give us our password, which is MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
