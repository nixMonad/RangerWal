# RangerWal
Use ranger to select the background to use with pywal.
This way you can get a preview of the image before you use it with pywal.
You can also set your wallpaper folder permanently(meaning you don't need to type it againg next time), by either passing the path as an argument :
```bash
	./rangerwal YOURPATH
```
or editing a file called .wallpaperpath in your home directory:
```bash
	echo YOURPATH >> .wallpaperpath 
```
just appending the path would be fine since the script uses the last line of .wallpaperpath as the path to use.


