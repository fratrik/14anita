# Getting started

1. Download zip (green "Clone or download" button)
2. Extract all files and run "jtree-win.exe" (Windows 7 or higher) or "jtree-macos" (MacOS).
3. Open the "Queues" tab, "play" the Queue to start a session.

# Running a session

1. Once you are ready to leave the training phase, use "Advance slowest" button to advance everyone out of the training phase. This is the only way to get out of the training phase.

2. After the session is finished, payment info is in the following variables
chosenBlock: the selected payment block, 0 = block 1, 1 = block 2, 2-5 = block 3, 6-7: block 4
chosenRound: selected round of the selected block
payoff: the selected payoff object
payoffEURNow: how much to pay them now
payoffEURLater: how much to pay them in 2 weeks
payoffChocBar: the chocolate bar they get now, if any.

3. You can find payment info in a few places:
- The last few columns of the "Participants" table in the Admin UI.
- The last "PLAYERS" table in the output file. Use "Download output" to get the output file, then open it in a text editor or Excel. Look near the bottom for the last "PLAYERS" table.