# CS-1060-FinalProject

When you clone via git, you need to configure git to properly diff scratch .sb2 files.

You will need to run this within the cloned repository:

```git config --local diff.zip.textconv "unzip -c -a"```

What this will do is add the following to the end of ./.git/config
```
[diff "zip"]
        textconv = unzip -c -a
```

The appropriate changes have already been made to the `.gitattributes` file, so that can be ignored.
