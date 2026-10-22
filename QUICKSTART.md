# Fly RC-X Quick Start

Fly RC-X runs next to RealFlight Evolution. It watches your flying through RealFlight Link, calls each maneuver out loud as you land it, and scores your drills.

## 1. One-time setup

1. **Install Fly RC-X.** Run the installer. If Windows says "Windows protected your PC", click **More info**, then **Run anyway**.
2. **Turn on RealFlight Link.** In RealFlight, open **Settings**, then **Physics**, turn on **RealFlight Link**, and restart RealFlight.
3. **Turn off pausing when RealFlight loses focus.** In RealFlight settings, turn off the option that pauses the sim when its window isn't active. Otherwise the sim freezes whenever you click on Fly RC-X.
4. **Run RealFlight in a window or maximized, not exclusive full screen.** Fly RC-X draws callouts and the roll trainer over the sim, and exclusive full screen hides them.

## 2. Every session

1. **Start RealFlight and load an aircraft.**
2. **Open Fly RC-X.** Check the status tiles in the top-right corner:
   - **SIM: RUNNING** means Fly RC-X can see RealFlight.
   - **RF LINK: ENABLED** means RealFlight Link is on.
   - **FOCUS PAUSE: OK** means the sim keeps running while you use Fly RC-X.
3. **Pick a mode** from the home screen. **HOME**, in the top-left corner, brings you back from anywhere.

## 3. The modes

### Fly: free flight with callouts
Fly however you like. When you land a maneuver Fly RC-X recognizes, it says the name out loud and flashes it at the bottom of the screen. Everything you fly is recorded for Debrief.
- **Text on sim:** the size of the callout text over RealFlight, or off.
- **Voice:** spoken callouts on or off.

### Train: the training program
A curriculum of units, from your first loop to the blender.
1. **Open a lesson.** Each one explains the maneuver, how it's flown, and what usually goes wrong.
2. **Run a drill.** Fly the maneuver. Each attempt is scored and marked **PASS** or **MISS**.
3. **Pass enough reps to advance.** The drill shows how many passes you need. When a rep doesn't count, a **NOT COUNTED** note tells you why.
4. **Use RESET REP** to put the airplane back and start a fresh rep.

Lessons unlock in order as you clear drills.

### Rifle Roll Trainer
The strip at the bottom of the home screen. Press **ARM** and Fly RC-X puts the roll trainer over the sim: a roll-phase circle, the rudder bar, and your elevator. It can fly the rudder for you while you learn the timing.
- **Authority:** how much of the rudder the trainer flies. At 100% it flies all of it.
- **Hand-back ramp:** fades the rudder back to you over the session.
- **Rudder beeps:** a high tone one way and a low tone the other, so you can hear the timing.

Change these under **settings** on the strip. Press **STOP** when you're done.

### Debrief
Every Fly session and drill is saved. Open one to see each maneuver you flew, its execution score, and the faults in plain words.

### Library
Every maneuver Fly RC-X knows, with difficulty, prerequisites and notes. Maneuvers marked **SUPPORTED** are the ones it can recognize and call.

## 4. If something's not working

- **"RealFlight not detected":** start RealFlight and load an aircraft. Fly RC-X connects automatically once it's running.
- **RF LINK shows OFF:** turn on RealFlight Link (Settings, Physics) and restart RealFlight.
- **The sim freezes when you click Fly RC-X:** turn off RealFlight's pause-when-inactive option.
- **No callout text over the sim:** check that **Text on sim** isn't off, and that RealFlight isn't in exclusive full screen.
- **No voice:** check that **Voice** is on, and check your Windows volume.

**Updates:** when a new version is ready, a banner at the top of Fly RC-X says so. Click **Restart now**, or keep flying and it installs the next time you close the app. See the [fixes and updates](CHANGELOG.md) page for what changed in each version.
