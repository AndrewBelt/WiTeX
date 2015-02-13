
![WiTeX screenshot](https://raw.githubusercontent.com/AndrewBelt/WiTeX/master/screenshot.png)

# WiTeX
*If Donald Knuth had designed Wikipedia*

## Install
If you have a Wikipedia account, open your [Preferences](https://en.wikipedia.org/wiki/Special:Preferences), go to the Appearance tab, and edit the Custom CSS for the Vector skin.
Paste the line

	@import url("https://en.wikipedia.org/w/index.php?title=User:AndrewBelt/WiTeX.css&action=raw&ctype=text/css");

into the code editor (or the contents of [`style.css`](https://raw.githubusercontent.com/AndrewBelt/WiTeX/master/style.css) itself if you prefer to manage your own copy), and save.

Alternatively, you can load the CSS using a browser plugin (such as [Stylish for Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome) or [Stylish for Chrome](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe)) for the domain `https?://*.wikipedia.org`.

For better alignment of mathematical equations, you can enable MathML or Mathjax in the Appearance tab.

#### I want the old Wikipedia design back!

There is no longer a link to the Preferences page on Wikipedia, so [here's the URL](https://en.wikipedia.org/wiki/Special:Preferences).

Change the skin to something else, apply, and remove the Custom CSS from the Vector skin.
Or, you could manually go to this URL while logged in:

https://en.wikipedia.org/w/index.php?title=Special:MyPage/vector.css&action=edit
