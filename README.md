# 5-a-side Score

A one-page scorekeeper for the kids' 5-a-side games, made for an iPhone on the sideline.

- Match clock with two halves of 25 or 20 minutes each (50 or 40 minutes in total).
  When a half's time is up the clock flashes, beeps and keeps counting added time
  until you tap **End 1st half** / **End game**. You can also end a half early.
- Subs reminder at the quarter mark (halfway through each half, e.g. 12:30 and 37:30):
  grey countdown, then amber "get ready" with a beep 2 minutes before, then a flashing
  red **SUBS NOW** with three beeps until you tap **Done** (or a minute passes).
  The label shows which quarter you're in (Q1–Q4).
- Team name defaults to Partick Thistle (editable before kick-off).
- One button per player (Alexander, Ashton, Ayaash, Carter, Remy, Spike) plus an
  opposition button. Each tap logs the goal with its match time and the running score.
- Tap a logged goal to change who scored or delete it; each new goal also has a short Undo.
- Tapped Kick off, End half or End game by mistake? Tap **Undo** in the pop-up that follows.
  **Reset game** (bottom of the page) puts the clock back to 00:00 at any point; at full
  time it becomes **Delete result**. Past games can also be deleted from **History**.
- **Share** sends the result and timeline to Messages/WhatsApp.
- Finished games are kept on the phone under **History**, with season W-D-L and goal totals.
- Works offline once opened, and survives the phone locking or the page reloading.

## Putting it on the iPhone

1. In GitHub: repo **Settings → Pages**, set *Source* to *Deploy from a branch*, pick the
   branch with these files and `/ (root)`, and save.
2. Open the Pages URL (e.g. `https://utx.github.io/score/`) in Safari.
3. Share button → **Add to Home Screen**. It then opens full screen like an app.

Data is stored in the phone's browser storage, so history lives on that one phone.
The beep follows the iPhone's silent switch; the flashing alert always shows.
