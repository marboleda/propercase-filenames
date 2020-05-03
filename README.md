## Filename "ProperCaser"
This is a program that fixes the metadata in files so that the casing of their titles is correct.

I created this when I found that .mp3 files in mixtapes I downloaded would have song titles in incorrect casing (e.g. "i love it all" instead of "I Love It All").
It felt disorganized having these titles in my music players, and manually changing the titles was time-consuming and repetitive.

This program will take all the files in a given directory and fix the casing.

## Languages
- C#

## To-Do
- Create UI for easier use. Right now this works by feeding in a path to the command-line, but I want to eventually make this a Windows utility.
- Implement a recursive version so that it can fix the files in several directories at once, not just a "flat" version that affects all files at one level.