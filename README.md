# CChatGUIDStatsLogger-1.0.0.2-ty_gerMOD
Unofficial Version of CChatGUIDStatsLogger version 1.0.0.2

This is the unofficial version of the "CChatGUIDStatsLogger-1.0.0.2" plugin for the game server managing program Procon. XpKiller wrote the original official plugin version. My modification is only an extremely tiny, easy modification in comparison to all of his very hard work.

Since XpKiller has abandoned this project and since there are a couple errors which needed to be fixed, I have modified and I am distributing the modified [unofficial] version.

Changes:
In CChatGUIDStatsLogger.inc file, the following items were changed:
- Line 462 through 545: Added additional weapon keywords.
- Line 4367: Fixed error in query which caused !top10 weapons query to fail.
- Line 5489: Fixed null primary key problem which caused incompatibility with MySQL version 5.7.3 m13 and up.
