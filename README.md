# Garden-Gnome-Gruvbox
Garden Gnome Gruvbox is a Gnome desktop eviroment inspired by earthy tones and witchy aesthetics.

ChatGPT called it,
"A charming and enchanting theme that brings a touch of the mystical to your digital realm. Get ready to be spellbound!"
Rating it 4 out of 5 mosquito bites.

---------------------------------------------------------------------------------------------------------------------

This is as best of a walk through as I can make for the Garden Gnome Gruvbox (GGG) set up.
GGG was designed on Pop OS. If you are not on Gnome I may not be able to help you.

You will need these applications.
  Gnome extension manager (I believe this is available in the pop shop)
    https://extensions.gnome.org/
  Gnome Tweaks (I believe this is available in the pop shop)
    https://itsfoss.com/gnome-tweak-tool/
    https://wiki.gnome.org/action/show/Apps/Tweaks?action=show&%3Bredirect=Apps%2FGnomeTweakTool
  Pywal
    https://github.com/dylanaraps/pywal
  Conky
    https://github.com/brndnmtthws/conky
    https://itsfoss.com/conky-gui-ubuntu-1304/
      the conky config file is in the repo along with the font and backgrounds.
  If you use Firefox or Librewolf I recomend using Firefox Color to theme the browser
    https://color.firefox.com/
  If you use Logseq for note taking this is the theme I currently use:
    https://github.com/stdword/logseq-bujo-theme

The gnome extensions you will need are:
  ArcMenu
  BackSlide
  Blur my Shell
  Color Picker
  Dash to Panel
  Just Perfection
  Rounded Corners
  User Themes
  Vitals
  --On Pop OS you may need to disable "Cosmic Dock" in gnome extensions

You will need to install Themes, Icons and a cursor.
Here is how:
  https://itsfoss.com/install-switch-themes-gnome-shell/
Here are the Themes, Icons and cursor:
  Sunrise GTK Dark Theme:
    https://www.pling.com/p/1258305
  Buuf For Many Desktops
    https://www.gnome-look.org/p/1012233
  Bibata Modern Amber
    https://www.gnome-look.org/p/1914819

I use Kitty as my terminal. I love it! it's great to learn on and there are tons of folks who cover Kitty config files.
My terminal theme is made with Pywal. 
In my experience pywal seems to download an outdated version of its Gruvbox preset with only 8 colors. 
I have provided a json file with 16 colors you can add to:
.../pywal/colorschemes/dark

run:
wal --theme garden-gnome-gruvbox-pywal -b "120e0d"

If you want a different terminal background color replace "120e0d" with whatever color better suites your needs, but this is the color that I use in other configurations.

VSCodium :) or vscode :( has a pywal extension called Wal Theme. This will match your vscodium / vscode theme to your terminal.
If you want a vscodium / vscode theme that is a combination of the garden-gnome-gruvbox-pywal and Sunrise GTK Dark Theme you can use mine.
Download the gruvbox-garden-gnome-theme folder and place it in:
~/.vscode-oss/extensions


I turn Window Titles off system wide and use gestures to full screen, minimize or close windows.
this is not something I feel particularly comfortable sharing as I don't understand it enough to prevent people from causing problems for themselves.

I will work on this more overtime and continue to provide more details on settings and options. let me know if you have questions and i will do my best to answer.
Have fun!!
