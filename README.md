# iOS-Themes

A collection of icons, widgets, and wallpapers for iOS.

## Minimalish Theme
![Screenshots of my minimalish theme](https://raw.githubusercontent.com/jpasholk/iOS-Themes/main/minimalish-icon-theme/minimal-tranparent-icon-theme-preview.png)

In this theme I use the Shortcuts app to help create the transparent icons and set them as "bookmarks" on the homepage to act as app icons, and add additional functionality to the Phone & Settings icons.

Perhaps I'll do a write up on how it's done in the future, but all that information can be found online elsewhere.

### ShortPhone

After finding that wallpaper and creating some icons for the dock, I was inspired to create a Shortcut for the Phone app. I realized that I hardly ever use the app itself, and instead just answer calls or ask Siri to call people.

The only time I open the app is to occaisionally access Favorites, Recents, or Voicemail.

So I set out to create a Shortcut that would let me access all of these funtions easily without opening the app itself. The idea is that I would place the options that I use more frequently closer to the bottom of the screen.

#### ShortPhone Features

- Connect - Open a menu to let you share your contact through card with the Share Sheet, or QR code.
- Add Contact - Opens the Add Contact Sheet
- Open - Opens the Phone app to the last tab (what tapping the app icon would do)
- Voicemail - Opens the voicemail tab
- Contacts - Opens the contacts tab
- Recents - Opens the recents tab
- Favorites - Opens the favorites tab
- Favorite Contacts - The menu has room for three favorite contacts before having to scroll, at least on my iPhone 13 Pro Max.

***

#### SCSettings Features - Copied From The RoutineHub Page

Instead of opening Settings, tapping the icon will run this Shortcut.

##### Show Information About Your Device

When running this Shortcut it will display some information about your device and the network it is connected to, among a few other useful pieces of information.

##### Information Shown When Running The Shortcut

* iPhone hardware version
* iOS Version
* Current Wi-Fi network
* IP address
* ~~VPN connection status~~ Removed in 2.0
* ~~Device storage remaining~~ Removed in 2.0
* ~~Device uptime~~ Removed in 2.0

##### Turn Off Wi-Fi & Bluetooth

The control center Wi-Fi and Bluetooth toggles only disconnects for 24 hours, which can be annoying if you actually want to just turn them off. The first option that appears will let you completely turn it off, as well as show if Wi-Fi is on or off. Since there's no easy way to track if Bluetooth is connected, it's not a dynamic icon.

##### Toggle VPN Settings

Open a menu that allows you to toggle VPN on or off, as well as toggling Connect On Demand.

##### Silence Unknown Callers

This setting should be on at almost all times IMHO, but it is buried under four taps and it can't be toggled with Siri. 

Luckily, Shortcuts supports turning it on and off with a native action. ~~Since there's no way to track if it's on or off, Toolbox Pro Global Variables must be used to track its state. Because of that it's best to turn it on before running, and only toggle it via this Shortcut.~~

##### Restart Your Device

Easily restart your device from the main menu.

##### Shut Down Device

Easily shut down your device from the main menu.

##### Access Settings That Apple Buried

This Shortcut includes several links to useful sections of the Settings app that a lot of power users likely access more than they know.

##### Settings Shortcuts:

- Analytics Data
- Privacy Report
- Private Relay (added in 0.7)
- Hide My Email (added in 0.9)
- Screen Time -> Content & Privacy Restrictions (added in 0.9)
- Personal Hotspot (added in 0.8)
- Clear Website Data
- Camera Format (added in 0.7)
- iPhone Storage
- Search Passwords (moved to main menu)
- Battery Settings
- AirDrop Settings

***

## Links

* [SCSettings - Access Burried Settings And Toggles Quickly](https://routinehub.co/shortcut/17931/)
* [ShortPhone - Quickly Access Common Phone Actions](https://routinehub.co/shortcut/19388/)

## Support

Help support my work! I have a full-time job and like to mess around with this stuff on my own time. Donatations are insanely motivating! 

<a href="https://www.buymeacoffee.com/jpasholk" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>