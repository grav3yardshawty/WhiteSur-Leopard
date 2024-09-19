# WhiteSur Leopard
Old Safari theme for firefoxon linux, based on the WhiteSur firefox theme by vinceliuice 

![Screenshot 1](https://i.imgur.com/lSuLtf7.png)

![Screenshot 2](https://i.imgur.com/LZlv6VZ.png)

# Make sure to turn title bar on in the firefox customization screen

I'm not entirely sure but i believe this theme only works properly on linux(and barely at that), specifically KDE Plasma with a matching aurorae theme. 
feel free to try it if you are on another OS though

If you are however on KDE Plasma, I would highly reccomend this [Aurorae theme](https://store.kde.org/p/1002696) for the titlebar to blend properly

The theme is super unfinished, and i'm not actually good at css at all so it probably won't actually get finished

So if you want, feel free (please do) to fork and make it better if you are good at css. Though, it's effectively just a bunch of custom styling slapped onto and mixed into an entirely different theme, so I'm sure the code 
is incredibly messy by the standards of those who know what they're doing

# Installation 

Embarassing but necessary heads up, for the life of me i cannot figure out how to get the ssl icons to change without pasting the actual location of the file as
the url for the icon in the css the same way you would "cd (directory)" to it, so while you're in the profile folder, i'd highly reccomend going into:

chrome/WhiteSur/parts/headerbar-urlbar.css

scroll all the way down, and replace the user and firefox profile folder name in 
"list-style-image: url("/home/mini/.mozilla/firefox/krl9hazs.default-release/chrome/WhiteSur/icons/folder-locked-symbolic.svg")
with your user folder and profile folder

1. Locate your firefox profile folder
   (If you are unsure where it is, you can find it by typing "about:profiles" in the firefox url bar, and clicking "Open Directory" on the Root directory of the profile in use
 in 
2. Paste the "chrome" folder from the repository into the profile folder
3. Restart firefox, and enjoy! at least until you realize how broken the theme is

You will also most likely want to customize the toolbar to put the buttons to the right places. If you're used to them being in a certain spot, this theme will probably be really annoying to use

At the very least its pretty to look at until you click too many buttons

   At the very least its pretty to look at until you click too many buttons
