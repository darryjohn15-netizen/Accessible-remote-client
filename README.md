# Accessible-remote-client. 
 Accessible Remote Client is a remote access and control app for blind, low-vision and visually impaired people, and for everyone who uses any Android screen reader, such as TalkBack, Commentary Screen Reader (Jieshuo+) and others. It connects Android to Android, and Android to a Windows computer running NVDA. You only need a server domain and a shared secret key. Phone-to-phone connections are end-to-end encrypted through a relay server. Phone-to-computer connections are encrypted between each device and the server.
Developer: Darry John Sarmiento.
Special Thanks
Nins Videña and Maria Teresa Olvido
Thank you for your help throughout this journey and for pushing me to develop this project. Your support, ideas and encouragement kept me going, even on the days when the work felt too hard to finish. Every test, every piece of advice and every word of motivation helped shape this app into what it is today. This project is as much yours as it is mine. I'm truly grateful to have worked on it with both of you.
Both phones must use the same screen reader. The app works with any Android screen reader, but different screen readers, such as TalkBack and Commentary Screen Reader (Jieshuo+), use different gestures, focus handling, actions menus and announcement timing, so a gesture or focus change sent from one screen reader can be understood differently on the other phone and cause wrong actions or glitches. The app checks this when you connect and pauses remote control until both phones match. A phone with no screen reader running, for example a sighted helper's phone, is allowed.
All help is in one place, in short sections: Quick Start, Setup, Screen Reader Configuration, Connection, File Transfer and Media Streaming, Sounds and Announcements, the two computer sections, Keyboard Commands, Troubleshooting, and Contact. Each section page uses headings, so you can jump through it by heading. Version 2.4.0.
Accessible Remote Client: changes made today (Tuesday, November 17, 2026)

KEYBOARD AND F11

- F11 switches the keyboard between the phone and the computer, both ways, from any app.- The keyboard starts on the phone, so you decide when it controls the computer.
- Holding F11 a little too long used to send F11 to the computer by mistake. Fixed.


NOTIFICATIONS

- The "Disconnected" notification no longer keeps coming back after you disconnect, stop, or force close the app.- While the app waits for the computer, it shows one notification with a Stop button.
- Swiping that waiting notification away now ends the waiting, the same as Stop, and it does not come back.


CONNECTING

- Connect to previous session: you reconnect with only the security key.FILES AND MEDIA

- If the connection drops while a file is being sent, you hear that it is paused, and it finishes by itself when the connection is back. If the session ends first, the unfinished file is removed and you are told.
- A failed file transfer now gives the reason in plain words instead of a code.
- After a big file arrives, the app says it is checking the file, so the silence makes sense.
- The Media Player says in plain words what went wrong when something cannot play.
- A video or song request nobody answered in 10 minutes now says nobody answered, instead of "declined".


SCREEN

- Screen sharing: the picture now turns with the Client phone when it is turned sideways or upright.
- Very long screens now come in parts, so nothing is lost. You hear, for example, "Part 1 of 3. Choose Next part to hear more."
- Move through parts with the Next part and Previous part buttons, in the screen reader's actions menu, or with Control+Page Down and Control+Page Up on a keyboard.
- Screens that fit in one piece work exactly as before.
- A screen can have up to 10 parts. Past that, the last part says the rest was cut short.
- If the other phone has an older version, the screen is cut as before, and you hear once: "This screen was cut short. Scroll on the Client phone to hear the rest."


 You decide when the keyboard controls the computer, and F11 switches both ways from any app."
INSTALLING AS AN UPDATE