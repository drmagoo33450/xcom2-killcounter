﻿TL;DR: Tactical UI now shows you how many enemies you've killed, the remaining
	   count and how many are currently active.

This mod adds a set of (very) simple counters to the Tactical UI. It shows you
how may enemies you've killed so far, how many are remaining (or the total
count, this can be changed in the config) and how many are currently activated
and after you (you can disable this in the ini if you dislike it).

It will only show the number of remaining enemies (or the total) in a mission
as long as you've already build the ShadowChamber (you can change this as
well in the ini).

So this mod doesn't show you anything which you didn't already know, but who
does exactly count how many aliens have been killed so far or how many are
currently active? While the total enemy count will go up whenever reinforcements
arrive, this also isn't something you didn't already knew (as long as you
counted fast enough). In case you dislike this, there's an ini option to
disable the total count. Same goes for the count of the currently active
enemies - technically not cheating, but somebody might dislike it -> tweak the
ini until you like it.

There are already a couple of settings you can set via inifiles. Below is a
listing of the default values in XComKillCounter.ini:

[KillCounter.KillCounter]
; Setting this to true will never show you the total number of enemies in a mission,
; even when you have access to the ShadowChamber so you already know it.
neverShowEnemyTotal=false

; The exact oposit from above - set it to true and you'll get the enemies total always
; even though you havn't build the ShadowChamber yet. Please note that this outrules 
; the setting from above - this one takes precendence, always.
alwaysShowEnemyTotal=false

; If set to false, the total active enemy count is never shown.
alwaysShowActiveEnemyCount=true

; Some people like it this way, some the other. Set it to false and you'll get the total
; count of enemies, set it to true and you'll get the remaining count.
showRemainingInsteadOfTotal=true

[KillCounter.KillCounter_UI]
; Disable coloring of all numbers
noColor=false

This mod is still in early development and likely to develop more features (and
bugfixes whenever needed). I'll do my best to keep it working, but this may
take a while as real life is a priority way before XCOM.

Possible future features:
 - Show the names (and count) of each enemy type killed, maybe in a tooltip. If
   you have any other idea how to visualize this properly (I'm not a UI 
   designer) please leave a comment [LOW]
 - Give players the option to not count reinforcements into the total count
   [LOW]
 - Give players the option to move the UI wherever they please [HIGH]
 - Give players the option to disable the remaining/total count in story
   missions where the count is rather high and it adds to the 'thrill' of
   those missions. [LOW]

Features marked with [LOW] are questionable and might not be useful at all.
Please feel free to leave a comment if you do think a features marked as [LOW]
is worth implementing and I'll see if I raise the priority of it.

This mod is open source: https://github.com/Luminger/xcom2-killcounter