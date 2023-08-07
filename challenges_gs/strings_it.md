# Challenge: strings it - 100p

## Description
Can you find the flag in file without running it?

## Process
Given the challenge name and the fact that the file is called *strings* I quickly got the hint that the ``strings`` command should be used here. Running strings on the given file (``string strings``) you get a bunch of text output. I didn't want to manually scroll through all of the text so I decided to combine the strings command with grep i.e. I ran ``strings strings |grep "picoCTF"`` which gave me the flag.