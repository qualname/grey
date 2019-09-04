# Grey
...because it's almost black.

### What is this?

This is my fork of *Black, the Uncompromising Code Formatter*.  
You probably do not want to use it! I highly recommend you try the
original project (found [here](https://github.com/python/black)) instead.

###  But why?

*Black* prefers double quotes (`"`) over single quotes (`'`), and will
replace the latter with the former. Additionally, the option to go single-quotes-first
was rejected by the author(s) of *Black*. (Relevant discussion
[here](https://github.com/python/black/issues/594))  
Since single quotes are *clearly* superior, I decided to fork the project!

### So what did you change?

This fork is almost identical to *Black*, but prefers single quotes over double
quotes (except for function docstrings).

### That's all?

That's all.

### Was this really necessary?

No, probably not! In fact I do not recommend you use this fork. If you prefer
single quotes over double quotes like I do, I advise you use *Black* with
`--skip-string-normalization` parameter set. Most find that to be an okay-ish
compromise.  
That being said I will keep this fork up-to-date with black-master because
I use it in my personal projects, so if you *really*, **really** dislike double
quotes, *and* want your formatter to normalize strings, feel free to try it!
