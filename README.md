# mac-big-sur-dynamic

### Installation
Change directory to your Pictures folder.
```sh
cd Pictures
```

Create a Wallpapers directory if it doesn't exist already.
```sh
mkdir Wallpapers
```

Clone this repo into "Wallpapers" (/home/user/Pictures/Wallpapers).
```sh
cd Wallpapers
git clone https://github.com/jarednthomas/mac-big-sur-dynamic
```

Fix paths to images in xml file by replacing my user paths (/home/jared/) with your username.
```sh
cd mac-big-sur-dynamic
whoami
sed -i 's/jared/your_username/g' big_sur_dynamic.xml
```

Set background to xml file.
GDM Steps: Tweaks > Appearance > Background > Select XML File
