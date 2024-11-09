Original: steam://url/CommunityFilePage/3050040845</url>\
I remake it to look better.<br/><br/>


***CONFIG***\
Turn on "Show color options" and changes: 
+ Brightness: 52
+ Contrast: 60
+ Saturation: 60
+ Hue shift: 50\
Make sure you checked "Audio recording" to get Audio Visualization.<br/><br/>

***IMPORTANT***\
Make sure you selected `Enable`/`Ultra` `Post-processing` in `Wallpaper Engine settings` because i used bloom for wallpaper.<br/><br/>

***BEST PLAYBACK SETTINGS (My opinion)***\
Other application focused: `Keep running`<br/>
Other application maximized: `Pause`<br/>
Other application fullscreen: `Stop (free memory)`<br/>
Other application playing audio: `Mute`<br/>
Display asleep: `Stop (free memory)`<br/>
Laptop on battery: `Keep running`<br/>
FPS: depend on your computer: lowest is `24fps`, highest is max if you want :))<br/><br/>

***HOW TO INSTALL MANUAL AND EDIT***
1. Copy `letter_ii_remake` folder to *`"X:\Steam\steamapps\common\wallpaper_engine\projects\myprojects\"`* or *`"C:\Program Files (x86)\Steam\..."`* - if you installed steam in C disk.
2. Restart wallpaper engine and you can see a duplicate wallpaper. Select it and click `Open in editor`. Enjoy!<br/>
You can also change the `title name`. In the wallpaper engine, select a wallpaper and `right-click` -> `open in explorer`. Right-click `project.json` -> `edit in notepad`, find *`"title" : "Letter II Remake (Pls read my description)",`*
and change title you want. Ex: *`"title" : "Letter II Remake",`*<br/><br/>


***RECOMMENT***\
I recommend you use `TranslucentTB` to make your taskbar look better.\
Link: https://apps.microsoft.com/detail/9pf4kz2vn4w9?hl=en-US&gl=US</url>\
After installed open and `right-click TranslucentTB in System tray icon` -> `Advanced` -> `Edit settings`. And replace it with this code:
```
// See https://TranslucentTB.github.io/config for more information
{
  "$schema": "https://TranslucentTB.github.io/settings.schema.json",
  "desktop_appearance": {
    "accent": "clear",
    "color": "#00000000",
    "show_peek": false,
    "show_line": false
  },
  "visible_window_appearance": {
    "enabled": true,
    "accent": "clear",
    "color": "#00000000",
    "show_peek": true,
    "show_line": false,
    "rules": {
      "window_class": {},
      "window_title": {},
      "process_name": {}
    }
  },
  "maximized_window_appearance": {
    "enabled": true,
    "accent": "normal",
    "color": "#00000000",
    "show_peek": true,
    "show_line": true,
    "rules": {
      "window_class": {},
      "window_title": {},
      "process_name": {}
    }
  },
  "start_opened_appearance": {
    "enabled": false,
    "accent": "normal",
    "color": "#00000000",
    "show_peek": true,
    "show_line": true
  },
  "search_opened_appearance": {
    "enabled": false,
    "accent": "normal",
    "color": "#00000000",
    "show_peek": true,
    "show_line": true
  },
  "task_view_opened_appearance": {
    "enabled": true,
    "accent": "normal",
    "color": "#00000000",
    "show_peek": false,
    "show_line": true
  },
  "battery_saver_appearance": {
    "enabled": false,
    "accent": "opaque",
    "color": "#00000000",
    "show_peek": true,
    "show_line": false
  },
  "ignored_windows": {
    "window_class": [],
    "window_title": [],
    "process_name": []
  },
  "hide_tray": false,
  "disable_saving": false,
  "verbosity": "warn"
}
```
<br/>
I also recommend you turn off `Fast startup`. It looks like your computer sleeps/hibernates instead of truly shutting down, and it sometimes can cause bugs/errors.<br/>
Link: https://support.lenovo.com/au/en/solutions/ht513773-how-to-enable-or-disable-fast-startup-on-windows-11<url/><br/><br/><br/>

***A BUG I FOUNDED IN WALLPAPER ENGINE***\
You can't change wallpaper, or wallpaper doesn't change and is not working? (Windows 11)<br/>
Fix: `Settings` -> `Personalization` -> in `Select a theme to apply` select `Windows(dark)` or `Windows(Light)` -> `Background` -> in `Personalize your background` select `Solid color`.<br/>
If it still doesn't work, open `wallpaper engine` `settings` -> `General` -> Uncheck `Override wallpaper image`. And then restart your computer.

<br/><br/>
**I HOPE YOU ENJOY IT (^_^)<br/> MADE WITH LOVE ❤️**
