Godot 4.5 dev5 exported HTML web game crashes in itch.io embed on mobile browser when using audio. "Compatibility" mode used in Godot 4.5 dev5.

I created this simple demo game with buttons that play sounds. The buttons also get pressed automatically in order to keep playing sound.

Demo: https://mellowminx.itch.io/audio-test-godot-4-5-dev-5

Password: godot

Project files: https://github.com/mellowminx/godot-4-5-dev-5-audio-test​

Game crashes/reloads after 1-3 mins

Tested on iOS Chrome and Safari

---

I also replicated this same demo game in Godot 3.5.3. The exported HTML web game embedded on itch.io seems to run with no issues. "OpenGL ES 2.0" mode used in Godot 3.5.3:

Demo: https://github.com/mellowminx/godot-3-5-3-audio-test

Password: godot

Project files: https://github.com/mellowminx/godot-3-5-3-audio-test

Tested on iOS Chrome for about 30 mins

---

Note: I also tried exporting with Godot 4.4.1 and it seems to have the same issue with the web game's audio on mobile browser. I also tried exporting using Godot 4.2.2, but the game wouldn't even load due to a SharedBufferArray error.

---

Update: I tried exporting with Godot 4.3 and it seems to work!

Demo: https://mellowminx.itch.io/audio-test-godot-4-3

Password: godot

Project files: https://github.com/mellowminx/godot-4-3-audio-test

Tested on iOS Chrome for about 15 mins
