# Streamlabs-For-Linux
Yeah! You know that theres no official release for that and you might be told: "Just use OBS Project with Streamlabs Extension". But what if you need to use streamlabs? Heres the tutorial..


# Install wine And winetricks first.
Use your package downloader to download the packages ```winetricks``` and ```wine```

For example:

```sudo pacman -S winetricks```
```sudo pacman -S wine```

Or

```sudo apt install wine```
```sudo apt install winetricks```



# Get everything you need from winetricks

First off you need to run: ```winetricks corefonts``` To install fonts so, you see something!

Then type ```winetricks```

On my Manjoro Linux installation it opens an UI, In it press "Select the default wineprefix", Then steer to "Install an Windows DLL or Component. Then select: "vcrun2019, vcrun2017, vcrun2015 and dotnet9", Proceed to exit the UI after saving.



# Run the instalation, On Lutris (game preservation platform)

You can find lutris ANYWHERE just install it, And then follow these steps.

On the top left corner there should be an plus button, Go ahead, press it.

It will show an pop up saying "Add games to Lutris", Press "Install a Windows game from an executable" Now youll go through basic stuff, Naming it and everything but you have to go to streamlabs.com and download the installer, Then put it in, Thats all for Lutris its just an installer. Select the setup file as the installer for streamlabs and it will show ur streamlabs installation of course! Now go through the installation but dont forget to select the installation folder as  "z:/home/user/Desktop/Streamlabs" we are almost done.

After it installs, You should go to the folder where it is installed of course /home/user/Desktop/Streamlabs, and then select the .exe, it should work! Do all the setup stuff and you have an streamlabs all to yourself.





#### the look may differ on different distros
