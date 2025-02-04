Farming Scripts 0.1 for StoneStoryRPG
================================================

This work is based on the proir work of Matjaž Guštin which is located
[here](https://github.com/TheMatjaz/StoneScript) and released under the BSD 3-clause license.

This StoneScript code used in the **amazing** ASCII-art game [Stone Story
RPG](https://store.steampowered.com/app/603390/Stone_Story_RPG/)
to automate it.

DISCLAIMER
----------------------------------------

Compare the date of when the scripts were created (commit date)
to the [latest game releases](https://stonestoryrpg.com/releasenotes/).

I **cannot guarantee** the scripts still work properly with any newer
version of the game.


What is this?
----------------------------------------

The game Stone Story RPG allows you to write a script to automate the player's
behaviour in the levels, so you don't have to keep looking and change weapons
at the proper times. It's great to let the game loops the levels and farm
automatically.

This option is available after beating the final boss for the
first time. Once you do, you'll get the Mind stone, which can
be used to write the script (or to paste an existing one into it).

- [Official intro to scripting](https://stonestoryrpg.com/stonescript/)
- [Full manual of the Stone Script language](https://stonestoryrpg.com/stonescript/manual.html)


Usage
----------------------------------------

1. Clone this repository into a subfolder of the StoneScript directory (\*)
   called `myScripts`. On Windows the directory is:
   
   ```text
   %AppData%\LocalLow\Martian Rex, Inc_\Stone Story\<Steam ID>\Stonescript
   ```
   
   The cloning command should thus look like
   
   ```bash
   cd '.\AppData\LocalLow\Martian Rex, Inc_\Stone Story\<Steam ID>\Stonescript\'
   git clone https://github.com/arcath-/StoneScript-Automation.git myScripts
   ```

2. Copy-paste the content of the
  [mindstone.txt](https://raw.githubusercontent.com/arcath-/StoneScript-Automation/master/mindstone.txt)
  file into the in-game Mindstone UI. This will load all other sub-scripts,
  one per level.

3. Modify the variables in 
   [loadouts.txt](https://raw.githubusercontent.com/arcath-/StoneScript-Automation/master/loadouts.txt)
   file to match your in inventory items. See comments at top of file for formatting.

3. Modify the scripts as you please for your own playing.
   Hold TAB for debug information while playing a level.
