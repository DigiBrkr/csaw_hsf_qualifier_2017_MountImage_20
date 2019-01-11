# Mount Image
20 points
> We've detained Herbert. He had a flash drive on him, we've just imaged it for you.
> How do you mount disk image files to get their contents?
## Solving it

To solve this challenge, all you have to do is mount the `fat.fs` file with the following commands:

First we make a directory in the `/mnt` directory. The main reason we mount it in this specific directory is that it is where the system would mount a real secondary disk.
`# mdkir /mnt/fat`
Then we mount the image `# mount fat.fs  /mnt/fat`. You have to be in the directory of the image for this command to work.
Then `cd` into the directory.
`# cd /mnt/fat`

Once you are in the directory do an `ls `
```
root@kali:/mnt/fat# ls
fk1onhl4.default.zip  flag.txt  mypasswords.pdf
```
You will see a file `flag.txt`. As you can imagine the flag is in this file.
So to see the flag we type `# cat flag.txt` and that gives us our flag:
`flag{m4ybe_file_carve_next}`

