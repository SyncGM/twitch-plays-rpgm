Twitch Plays RPGM v1.0 by Enelvon
=============================================================================

Summary
-----------------------------------------------------------------------------
This grimoire uses my knowledge of dark magic to channel the corrupted power
of the internet's denizens into RPG Maker. By trapping their essences inside
the engine, they are forced to play the game to the best of their
(questionable) ability. You may observe their thoughts as they struggle
against one another to achieve success by watching the console, so this
grimoire's magic is best applied during playtesting. If you wish to look over
their thoughts at a later point or trap them during normal play, fear not--you
can log their wailing to a scroll, too.

Compatibility Information
-----------------------------------------------------------------------------
**Required External Reagents:**
None. This grimoire contains all of the necessary reagents for the rituals to
summon and bind the spirits of the internet.

**Known Incompatibilities:**
None.

Usage
-----------------------------------------------------------------------------
This grimoire is more-or-less plug and play. Drop it in a project and watch
as the tortured souls of the internet squirm for your amusement. You may,
however, wish to modify some of the chants used in the ritual in order to
achieve varying results, however. Each chant is described in the
SES::TwitchPlaysRPGM chapter of this grimoire.

Aliased Spells
-----------------------------------------------------------------------------
* `module DataManager`
- `self.load_database`

* `module Input`
- `self.update`

* `class Window_MenuCommand`
- `add_game_end_command`

* `class Window_TitleCommand`
- `make_command_list`

* `class Scene_Title`
-  `command_new_game`

* `class Scene_Map`
- `update`

* `class Scene_Battle`
- `start_party_command_selection`
- `prior_command`

New Spells
-----------------------------------------------------------------------------
* `module Input`
- `self.dir4`
- `self.dir8`
- `self.press?`
- `self.repeat?`
- `self.trigger?`

License
-----------------------------------------------------------------------------
This grimoire is made available under the terms of the MIT Expat license.
View [this page](http://sesvxace.wordpress.com/license/) for more detailed
information.

Installation
-----------------------------------------------------------------------------
Place this grimoire below Materials, but above Main.
