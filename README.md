# Glowbooth-Time-Stamp-Grabber

So you had a big night out partying at your ball/office-party/cult-end-of-year-event/whatever and that happens to have a photo booth. The next morning, with headache still pounding, you decide you want to download some photos from the rambunctious night! 

But ALAS! A problem! The photos downloaded directly from the glowbooth website haven't been timestamped! There are time stamps in the photo title at least...

But no again! The traditonal time stamp bash scripts don't work because the glowbooth people decide to add a _ and then a number for each number of photo groups!! A serious issue.

To avoid this ever happening again I made this bash script

To run just download the script file, chmod to allow it to run (`chmod +rwx ./script`) type the name of the photos you want to change, or make it so bash can read it (i.e. * to read every file in directory)

e.g.
```
$ ./script *.jpg # Will change timestamp of every file ending with .jpg in current directory
```

Known issues:
- Doesn't work with Glowbooth .gifs, could probably be an easy fix but I can't be fucked dealing with it tbh
- Majority of code was stolen from stack overflow answer [here](https://stackoverflow.com/questions/31351739/how-can-i-change-a-files-timestamp-from-the-file-name-in-linux)
- Code won't run on Windows, maybe Mac but I will not harass some random mate to use their mac to test
- Readme file is terrible and full of typos and punctuation, and splelling errors
