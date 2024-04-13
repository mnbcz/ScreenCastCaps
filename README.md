
# Screencast Keyboard - Keyboard, mouse, keystrokes on the screen.

This is keystroke visualizer for Windows. On screen display keystrokes, keyboard, and mouse. 

Designed specifically for creating screencasts and tutorials.
Used by instructors and YouTubers to create tutorials.

All pressed keys are displayed, not combinations. So, you can know which key was pressed and which is currently being held. Examples and tutorial can be found here.

To install, use [latest release](https://github.com/mnbcz/ScreenCast-Keyboard/releases)

The following features are supported:

- Moving the keyboard, or keystrokes, with the mouse.
- Resizing the keyboard with the mouse.
- Sound when pressing keys.
- Sound themes for keys. It is possible to create a theme yourself.
- Ability to change keystrokes style via css.



# Sound when pressing keys

By default, the sound of the keys is disabled.
You can enable this by right-clicking on the program in the tray and a menu will open.
Next select **Setting**. Scroll to the bottom and find the option **Keyboard and mouse sound**.
Turn on the switch on the right.
At the bottom there will be a list of sound themes for keystrokes.

## Installing the user sound theme

To create a sound theme yourself, you need to copy the `Mechanic brown` directory with the sound theme in the directory
`C:\Program Files\ScreenCast Keyboard\sounds`.
And put it in the directory
`C:\Users\<UserName>\AppData\Roaming\ScreenCast Keyboard\sounds`
And rename.
Next, replace the sound files in this directory.
In **Setting**, a new theme will appear in the list of sound themes.


# Custom keystroke style

To change the keystroke style, you need to go to the directory with the program, then to the `www` directory
`C:\Program Files\ScreenCast Keyboard\www`.
Copy the `keysList.css` file and place it here.
Next, edit the style file `keysList.css`.
Restart the program.


# Issues

If there are any problems with the program.
The sound lags when pressed, etc.
Select **Reload** from the menu.


