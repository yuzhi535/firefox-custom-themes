# custom-firefox-theme

Due to the height of top border is too big, I wanna make it smaller.

Just refer to [this repository](https://github.com/Tnings/CompactFox). Added the function of automatically showing the close button. 

## screenshots

![](images/Screenshot%202022-08-13%20at%2012.04.16.png)

![](images/Screenshot%202022-08-13%20at%2012.09.17.jpeg)

## Generic Installation

* Go to the wanted theme and click the download button.
* You should now be on the Github page for that topic.
* Below you should see a guide on how to install that particular theme and a few preview pictures. Anyway, here are some common steps for all themes.

1. Download the theme with the big green button: "Code" >> Download.zip
2. Open `about:config` page.
3. A dialog will warn you, but ignore it, ~~just do it~~ press the `I accept the risk!` button.
4. Search for these:

  + **`toolkit.legacyUserProfileCustomizations.stylesheets`**
  + **`layers.acceleration.force-enabled`**
  + **`gfx.webrender.all`**
  + **`gfx.webrender.enabled`**
  + **`layout.css.backdrop-filter.enabled`**
  + **`svg.context-properties.content.enabled`**
	Then make sure to **enable them all!**

5. Go to your Firefox profile.

  + Linux - `$HOME/.mozilla/firefox/XXXXXXX.default-XXXXXX/`.
  + Windows 10 - `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`.
  + macOS - `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX`.

6. Create a folder and name it **`chrome`**, then assuming that you already have cloned this repo, just copy the theme to `chrome` folder.
7. Restart Firefox.
