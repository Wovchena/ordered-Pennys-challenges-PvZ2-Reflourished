# Ordered Penny's Challenges PvZ2: Reflourished

Penny's Challenges are renamed here so they can be played in release order according to https://reflourished.fandom.com/wiki/Penny%27s_Challenge. Copy `.json`s and `.txt` to `Android/data/com.ea.game.pvz2_rfl/files/No_Backup/CDN.<ver.si.on>/levels/`. To determine the challenge type, check the remainder when dividing the in-game level number by 4:
1. Remainder `1`: `normal` challenge
2. Remainder `2`: `Veteran` challenge
3. Remainder `3`: `Saucy` challenge
4. Remainder `0`: `Hot Sauce` challenge

Some numbers are skipped because version modifiers aren't published for these levels. See https://reflourished.fandom.com/wiki/User_blog:MawDaSplatyBox2/Penny%27s_Challenge/Extra for challenge version difference.

The bonus challenges don't follow this numbering because only `LightUpMyNight.json` has the `Veteran` version. `modern*.json` is reserved for these bonus challenges and the numbering is plain.

[rename.py](rename.py) defines the mapping explicitly.
