# CS-1060-FinalProject

When you clone via git, you need to configure git to properly diff scratch .sb2 files.

Add the following to the end of ./.git/config
[diff "zip"]
        textconv = unzip -c -a

