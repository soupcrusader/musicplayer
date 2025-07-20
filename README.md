# musicplayer
have you ever wanted to be able to play your spotify playlists offline, but dont wanna pay for premium? this program allows you to play mp3 files from a chosen folder with the ability to skip and shuffle.  for use with spotdl (https://github.com/spotDL/spotify-downloader), which allows you to convert your spotify playlists to mp3s.


GENERAL INSTALLATION:

first off, you need to aquire the mp3 files. i use spotdl (see above link) to get my music as it can do entire playlists quite quickly, but the executable will work no matter how you get the songs. once you have them, place them all in a folder somewhere. it doesnt matter where (unless you have multiple drives, i havent tested how the program works with the executable and the song folder being in different drives so just keep them in the same one).

to run the program you need python3. I cant be assed explaining how to get python so just google a guide. honestly if you have a github account theres like a 95% chance you also have python installed so i probably dont need to explain this to you.

now, download the musicplayer file, pick the version that works for your OS. (assuming i make a version for anything other than mac)

MAC/LINUX INSTALLATION:

MAKE SURE YOU HAVE PYTHON INSTALLED, SEE ABOVE.

first off, download the mac version of the file. (this works with linux too i just forgot to call it mac/linux)

also if you are on linux replace the commands with the linux equivalent, im assuming that if you have linux you have at least a rudimentary understanding of stuff like this because i dont know why else you would run the os. (the command for the actual program doesnt need to be adjusted fyi)

once you have it downloaded, rename it to musicplayer.py. this makes it so you can run through python.

move the file to your users folder. dont place it inside a folder within the user, just keep it there. things break when you go beyond just the user folder.

now you gotta run the command "chmod +x ~/musicplayer.py". this makes the script executable.

now, run the command "pip3 install pygame". this is a python addon needed to make the script run.

next, open up your terminal and type in "python3 musicplayer.py (name of folder with mp3s)"


it should now start playing one of the mp3s in the folder at random.

this will work no matter your internet connection and without ads. good for long plane/car rides.
