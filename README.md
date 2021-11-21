# Basic-Media-Hotkeys
Basic media hotkeys for who don't have hotkeys in their keyboard.

## How to use?
Download the ".exe" file. Run the program. To exit just press; <kbd>Win + Ü</kbd> .

| Hotkey | Action |
| ------ | ------ |
| <kbd>Win</kbd> + <kbd>Q</kbd>  | Play/Pause |
| <kbd>Win</kbd> + <kbd>W</kbd>  | Previous song/media |
| <kbd>Win</kbd> + <kbd>E</kbd>  | Next song/media |
| <kbd>Win</kbd> + <kbd>Ü</kbd>  | Exit program |

## Auto Start with Windows
 * Press <kbd>[Windows] + R</kbd>
 * Type <kbd> shell:startup
 * Press <kbd>[Enter]</kbd>
 * Create shortcut or copy into folder.
  
### How it's Work?
 * It's a really simple code which i wrote with using [Auto Hotkey](https://www.autohotkey.com). Normally it was a ".ahk" file then i converted it into a ".exe" file to use more effectively and easily. I'm also uploading ".ahk" and ".txt" files for you to try or add something different. Have fun !
  ```
  #NoTrayIcon                  ; Hides the Tray icon from bottom-right.

  #q:: Send {Media_Play_Pause} ; Play/Pause function.
  #e:: Send {Media_Next}       ; Next song/media function.
  #w:: Send {Media_Prev}       ; Prev song/media function.

  #ü::ExitApp                  ; Exits app.
  ```
* There is a [Guide](https://www.autohotkey.com/docs/commands/Send.htm) for how the code is working and how can be improved.
  
### DON'T FORGET
 * Don't forget to close before starting to play any game with anticheat. There is nothing wrong with the program but **better be safe than sorry**.
