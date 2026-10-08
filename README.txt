MS. KAPLE'S KEYBOARD DETECTIVE AGENCY — V7 MOVING

WHAT CHANGED
- One scoring system only: POINTS.
- The home screen and game screen show total points and points until the next badge.
- Removed visible Case Score / Clue / Agency Points counters.
- Each case is now 5 rounds so students can move through the activities faster.
- Completed case files get a COMPLETE stamp.
- ALL bonus missions stay locked until all 8 core case files have been completed.

NO O / NO 0
- The letter O is excluded from every answer/code/question pool.
- The digit 0 is excluded from every answer/code/question pool.
- Alphabet Evidence only uses A–N and P–Z sequences.
- Picture File does not use an O clue.
- Place Value, Number Trail, Number Escape, and all bonus missions avoid 0.

PLACE VALUE
- Replaced the smallest/largest/middle-number task.
- Students now answer which digit is in the ONES place or TENS place.
- No hundreds-place questions.

MORE MOVEMENT
Core cases:
- Moving Evidence: evidence pieces gently move while students count.
- Letter Escape: correct letters move/jump the agent across the screen.
- Number Escape: correct numbers move/jump the agent across the screen.
- Picture clues gently bob.

Locked bonus missions:
1. Catch the Suspect — correct letters/numbers move the agent.
2. Evidence Rush — a letter/number races across the screen.
3. Laser Escape — a moving laser sweeps the screen and correct keys shut it down.
4. Crack the Vault — mixed letter/number secret code.

READ TO ME
- Home directions
- Points / badge status
- Every case card
- Every question and prompt
- Every bonus mission card and lock message
- Moving-game target prompts
- Reward, badge, and completion screens

REWARDS
- Rewards remain on screen until the student deliberately closes/continues.
- Typed letters/numbers remain visible in answer blanks.
- Wrong answers briefly appear in the blank before resetting.

GITHUB
Upload all files inside this folder to the root of the existing GitHub Pages repository.
If your existing repo already contains your Homebody/VAG font files, leave those files in place.


V7.1 FIXES
- Completed case cards now show a large diagonal SOLVED stamp across the card.
- Fixed reward/evidence screens where the click-to-continue handler could attach to the speaker button.
- Fixed the same issue on rank-up screens.
- Forced VAG for regular in-game text and buttons; Homebody remains on title-style text.
- Font-face now recognizes either VAGRoundedBlack.ttf / KAHomebodyClub.ttf or the original uploaded font filenames if those files already exist in the GitHub repo.


V7.2 RESET FIX
- The top RESET GAME button is now a true clean-slate reset.
- One click clears:
  • all saved case scores
  • all points/badge progress
  • every SOLVED case stamp
  • completed-case progress
  • bonus mission unlock status
  • temporary keyboard/reward/overlay state
- It immediately opens Case 1 at Question 1.
- This is intended to make teacher demos easy without manually clearing browser storage.


V7.3 AGENT HEADQUARTERS
- Main page now includes an AGENT BRIEFCASE.
- Six unique detective objects can be collected:
  Magnifying Glass, Secret Case File, Fingerprint Kit, Secret Camera, Spy Radio, Agent Briefcase.
- Each object is collected ONE TIME ONLY. No duplicate objects are added.
- Locked/unfound objects stay visible as empty/grey collection slots.
- Main page now includes a BADGE CASE showing every earned badge and locked future badges.
- EPIC SECRET AGENT appears in the badge case after all four bonus missions are completed.
- Bonus missions remain locked until ALL 8 case files are SOLVED.
- Each of the four bonus missions is tracked separately and gets a MISSION SOLVED stamp.
- Completing the fourth different bonus mission triggers a full-screen EPIC SECRET AGENT celebration.
- RESET GAME also clears briefcase objects, bonus completion, and Epic Agent achievement.
