# Modern-ThunderBird
A userChrome.css theme to make Thunderbird (78+) resemble Firefox 89+

![image](https://user-images.githubusercontent.com/30136040/206086881-d2111947-a77f-4e48-88bb-f314cfc51366.png)
*Updated tabs and toolbar*

![Updated dropdown menus](Screenshots/screen2.webp)
*Updated dropdown menus*

![Works with themes](Screenshots/screen3.webp)
*Works with most themes other than the default light theme.*

## Installation

1. Download the file named userChrome.css from this repo.
2. Open Preferences and scroll all the way to the bottom of the General tab.
3. Click `Config Editor...`
4. A dialog will warn you, but ignore it, press the `I accept the risk!` button.
5. Enable the following flags by right clicking and selecting toggle:

	+ **`toolkit.legacyUserProfileCustomizations.stylesheets`**

5. Go to your Thunderbird profile.

	+ Linux - `$HOME/.thunderbird/XXXXXXX.default-XXXXXX`.
	+ Linux (Flatpak) - `$HOME/.var/app/org.mozilla.Thunderbird/.thunderbird/b96p321h.default-XXXXXX`
	+ Windows 10 - `C:\Users\<USERNAME>\AppData\Roaming\Thunderbird\Profiles\XXXXXXX.default-XXXXXX`.
	+ MacOS - `Users/<USERNAME>/Library/Thunderbird/Profiles/XXXXXXX.default-XXXXXXX`.

6. Create a folder and name it **`chrome`**, then copy `userChrome.css` from step 1 to `chrome` folder.
7. Restart Thunderbird.

## Other Settings
You may notice that your thunderbird doesn't quite look like the first screenshot. To fix this, go to Menu > View > Density and set it to "Touch". Then change the font size to 12px

## End of Useful Life
You might have heard about the upcoming release of [Thunderbird Supernova](https://blog.thunderbird.net/2022/11/thunderbird-supernova-preview-the-new-calendar-design/) some time in 2023. Based on the screenshots, it seems like it may do away with tabs all together, so this theme may no longer serve much of a purpose after that point.
