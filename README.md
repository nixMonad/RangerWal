# RangerWal
Use ranger to select the background to use with pywal.
This way you can get a preview of the image before you use it with pywal.
In order to be able to use this script you can clone it and give it execution permission.
```bash
git clone https://github.com/emadist/RangerWal
cd RangerWal
chmod +x rangerwal
```
and to use it type:
```bash
./rangerwal
```
If you want to be able to run it from everywhere consider adding the folder the script is in, to your path or simply copy "rangerwal" to /usr/local/bin(note that this will require sudo permission) :
```bash
sudo cp rangerwal /usr/local/bin/
```
You can also set your wallpaper folder permanently(meaning you don't need to type it againg next time), by either passing the path as an argument :
```bash
./rangerwal YOURPATH
```
or editing a file called .wallpaperpath in your home directory:
```bash
echo YOURPATH >> .wallpaperpath 
```
just appending the path would be fine since the script uses the last line of .wallpaperpath as the path to use.
