# BugReport
Bug Reporting Form


Here’sabreakdownofcommonbugclassificationsingamedevelopment,alongwith
 examples:
 1. Visual Bug(Graphical/Art Issue)
 •
 •
 Definition: Issues related to graphics, UI, textures, models, lighting, or animations.
 Examples:
 ◦
 ◦
 ◦
 ◦
 ◦
 Texture not loading correctly (blurry or missing).
 Character model clipping through objects.
 Incorrect UI scaling on different resolutions.
 Animation glitches (e.g., floating NPCs, T-posing).
 Lighting/shadows rendering incorrectly.
 2. GameplayBug(Mechanics&BalanceIssues)
 •
 •
 Definition: Issues that affect game mechanics, player interaction, or balance.
 Examples:
 ◦
 ◦
 ◦
 ◦
 ◦
 Player gets stuck in terrain and cannot move.
 EnemyAInotrespondingorbehavingunnaturally.
 Broken gameprogression(e.g., a quest that won’tcomplete).
 Overpoweredweapons/skills ruining balance.
 Inconsistent hitboxes or collision detection.
 3. ProgrammingBug(CodeLogic&ScriptingIssues)
 •
 •
 Definition: Issues caused by coding errors or logic failures in the game’s scripts.
 Examples:
 ◦
 ◦
 ◦
 ◦
 Gamecrashesduetomemoryleaks.
 Incorrect variable handling causing unintended behaviors.
 Broken eventtriggers (e.g., cutscenes not playing).
 Save datacorruption.
◦
 Infinite loops causing freezes.
 4. AudioBug(Sound/MusicIssues)
 •
 •
 Definition: Problems related to in-game audio, voice lines, sound effects, or music.
 Examples:
 ◦
 ◦
 ◦
 ◦
 Backgroundmusicsuddenlystopsplaying.
 Incorrect voice lines triggering.
 Audio delay or desyncincutscenes.
 Soundeffects missing or repeating infinitely.
 5. Network/Multiplayer Bug(OnlineIssues)
 •
 •
 Definition: Issues affecting online connectivity, synchronization, or networking.
 Examples:
 ◦
 ◦
 ◦
 ◦
 ◦
 High ping causing player lag.
 Desync betweenplayers(e.g., player appears in different locations for each client).
 Matchmakingfailing or not finding players.
 Server disconnects/crashes.
 Player stats/items not saving correctly in online mode.
 6. PerformanceBug(OptimizationIssues)
 •
 •
 Definition: Problems that cause lag, frame drops, or excessive resource usage.
 Examples:
 ◦
 ◦
 ◦
 ◦
 SuddenFPSdropsinspecific areas.
 Memoryleaksleadingtocrashes after long play sessions.
 Unoptimized assets causing high CPU/GPUusage.
 Stuttering or input lag.
 7. Physics Bug(Collision/Simulation Issues)
 •
 •
 Definition: Bugs related to physics simulations, collisions, or ragdoll mechanics.
 Examples:
 ◦
 ◦
 Objects bouncing uncontrollably or flying into the sky.
 Players or NPCsgetting launched after touching certain surfaces.
◦
 laye s o 
Cs gett glau c eda te touc gce ta su aces.
 ◦
 ◦
 Vehicles floating instead of driving properly.
 Character falls through the ground.
 8. Scripting/Quest Bug (GameLogicIssues)
 •
 •
 Definition: Bugs affecting quests, mission progression, or scripted events.
 Examples:
 ◦
 ◦
 ◦
 ◦
 NPCsnotspawningforamission.
 Quest objectives not updating.
 Dialogue sequences skipping or repeating.
 Triggers failing to activate (e.g., doors not opening when they should).

------------------------------------------------------------------------------------------------------------------------
BugReportTemplate
 1. BugID:
 (Unique identifier for tracking the issue, e.g., BUG-0012)
 
2. Title:
 (Short, clear description of the bug, e.g., “Character model T-posing after respawn”)

 3. Category:
 (Select the appropriate bug type from below)
 ✅VisualBug
 ✅GameplayBug
 ✅ProgrammingBug
 ✅AudioBug
 ✅Network/Multiplayer Bug
 ✅PerformanceBug
 ✅PhysicsBug
 ✅Scripting/Quest Bug

 4. Severity:
 (Howcritical is this bug?)
◦
 ❗Blocker‒Preventsprogress,gameunplayable(e.g., gamecrashesonlaunch).
 ◦
 ◦
 ◦
 ◦
 ⚠Critical‒ Major issue, but gamestill functions (e.g., major performance drops).
 🔸Major‒Annoyingbutdoesnotblockprogress(e.g.,somemechanicsnotworking).
 🔹Minor‒Cosmeticissue(e.g.,slight texture glitch).
 ✨Trivial‒Notaffecting gameplaybutworthfixing (e.g., typo in UI).
 5. Steps to Reproduce:
 (Provide step-by-step instructions to reproduce the bug consistently.)
 arh. Start the gameandselect"NewGame."
 ari. Walk towards the caveentrance in Level 2.
 arj. Jumpovertherockwhilesprinting.
 ark. Observe that the character remains stuck in mid-air.
 6. Expected Result:
 (What shouldhappen?E.g., “Character should landbackonthegroundnormally.”)
 7. Actual Result:
 (What actually happens? E.g., “Character gets stuck in mid-air and cannot move.”)
 8. Screenshots/Videos (if applicable):
 (Attach any supporting media for clarity.)
 9. Logs/Error Messages (if applicable):
 (Include relevant crash logs, error messages, or console output.)
 10. System/Platform Information:
 ◦
 ◦
 ◦
 ◦
 GameVersion:(e.g., v1.0.5)
 Platform: (PC, PlayStation, Xbox, Switch, etc.)
 Operating System:(Windows11,macOS,etc.)
 HardwareSpecs:(CPU,GPU,RAM,etc.)
 11. Additional Notes:
 (Any extra details, potential workarounds, or links to similar reports.
