# EV3 Line Tracing Challenge (P6 Edition)
A simpler competition for Primary 6 students who have just learned EV3.  
Everyone can score points, and stronger teams can keep going to the next level.

This is the codebase that contains all the files that we will use in the Workshop.  
## Step 1: Download EV3 Classroom App
Download the App through this link:  
https://education.lego.com/en-us/downloads/mindstorms-ev3/software/  
Download the files and open the launcher.
## Step 2: Download All the files in the Lesson files
Download all the files in [Lesson files](./Lesson%20Files/)  
OR  
Download the entire repositry as a zip file and unzip it.
## Step 3: Lesson 1 and 2
Open the Files downloaded  
Follow the Lesson pace and slides.
## Step 4: Lesson 3 - 7  
These Lessons are to be done at your own pace.
After each lesson, notify one of us and we will ensure that you have done the exercise correctly

# Competition Rules
After finishing all the lessons, you can start preparing for the competition.  
You may change your robot's build and improve your code before the competition.

**Your mission:** Follow the black line from **START**, pass the checkpoints, then choose a path at the **FORK** and stop in an **END** zone.  
The further your robot goes, the more points you get!

![Map for EV3 Line Tracing Challenge (P6)](./Map.png)

## The Three Levels
The line is made only of **straight pieces**. They meet at different angles: gentle **45° bends** and one sharp **90° turn**.

| Level | Route | What your robot must do | Lessons that help |
|-------|-------|-------------------------|-------------------|
| **Level 1** | START → CP1 | Follow the line through two 45° bends | Line Tracing (Lesson 7) |
| **Level 2** | CP1 → CP2 | Turn **right 90°** at the yellow patch **T1** | 90° Turns (Lesson 4), Turning (Lesson 6) |
| **Level 3** | CP2 → FORK → END | At the red **FORK**, pick a path and stop inside its green END zone | All lessons |

### Level 3: Pick Your Path
| Path | Direction at the FORK | What's on it | Points |
|------|------------------------|--------------|--------|
| **Short path → END A** | Robot goes **left** | Two 45° bends, nothing else | Fewer points, easier |
| **Long path → END B** | Robot goes **right** | Longer line with two bricks to push | More points, harder |

You only get points for **one** END zone per run.

## What the Colours Mean
| Colour | What it is | What it means for your robot |
|--------|-----------|------------------------------|
| Black line | Tape on the mat | Follow it |
| Blue patch (CP1, CP2) | Checkpoint on the line | You have finished a level. Bonus if your robot beeps here! |
| Yellow patch (T1) | Turn marker on the line | Sharp turn: turn **right 90°** here |
| Red patch | The FORK | Choose your path: left to END A or right to END B |
| Orange brick (B1, B2) | Real brick on the long path | Push it into END B for bonus points |
| Green zone | END zone | Stop your robot here |
| Grey barrier | Real wall | Do not touch it |

**Every colour has one fixed meaning.** You don't have to guess.

## Scoring
### Level Points
| Reached | Points |
|---------|--------|
| Level 1: robot reaches **CP1** | 10 |
| Level 2: robot reaches **CP2** | +20 |
| Level 3: robot **stops** in **END A** (short path) | +20 |
| Level 3: robot **stops** in **END B** (long path) | +30 |

### Bonus Points
| Bonus | Points |
|-------|--------|
| Each orange brick **fully inside** END B | +10 each (max 20) |
| Robot **beeps or shows a sign** when it reaches each checkpoint | +5 each (max 10) |
| Robot stops in an END zone in **under 1 minute** | +10 |

**Maximum score: 70 points on the short path, 100 points on the long path.**

A checkpoint counts as reached when the front of the robot passes over the blue patch while following the line.

## Run Rules
1. **Starting:** The robot must be fully inside the START zone, facing the line (see the arrow on the map).
2. **Hands off:** After you press start, don't touch the robot. If you touch it, the run ends.
3. **Follow the line:** Your robot must follow the black line. It may leave the line only to make the sharp turn at the yellow patch.
4. **No shortcuts:** If your robot cuts across the mat to skip part of the line, the run ends.
5. **Barrier:** If your robot touches the barrier, the run ends.
6. **Time limit:** Each run lasts up to **2 minutes**.
7. **END zone:** At least **half of the robot** must be inside the green zone and the robot must **stop**. The run ends when it stops there.
8. **Keep your points:** If a run ends early (touching, shortcut, barrier, or time up), **you keep the points you already earned** in that run.
9. **Tries:** Each team gets **3 runs**. You may pick a different path on each run. Your **best run** counts.
10. **Reset:** The bricks are put back in the same places before every run.
11. **Tie-breaker:** If two teams have the same score, the faster best run wins.

## Robot Rules
- Use only parts from your EV3 kit.
- Your robot must fit inside the START zone (35 cm × 35 cm) at the start.
- You may change your code between runs, but the next run must start within 2 minutes.

---

## Setting Up the Mat (for facilitators)
Mat size: **200 cm × 120 cm** on a white or light surface. The map has a 10 cm grid to help with placing items.  
Positions below are measured in cm from the **top-left corner** (x = across, y = down). Every line piece is a straight strip of 2 cm black tape running between the points listed.

| Item | Size | Position |
|------|------|----------|
| START zone | 35 × 35 cm, grey/white outline | x 5 to 40, y 5 to 40 |
| END A (short path) | 30 × 30 cm, green | x 165 to 195, y 72.5 to 102.5 |
| END B (long path) | 35 × 35 cm, green | x 5 to 40, y 80 to 115 |
| Main line | 2 cm tape | (40, 22.5) → (70, 22.5) → (95, 47.5) → T1 (140, 47.5) → FORK (140, 72.5) |
| Short path line | 2 cm tape | FORK (140, 72.5) → (155, 87.5) → (180, 87.5), ending inside END A |
| Long path line | 2 cm tape | FORK (140, 72.5) → (115, 97.5) → (25, 97.5), ending inside END B |
| CP1 (blue) | 8 × 8 cm, on the line | (115, 47.5) |
| T1 (yellow) | 8 × 8 cm, on the corner | (140, 47.5) |
| CP2 (blue) | 8 × 8 cm, on the line | (140, 60) |
| FORK (red) | 8 × 8 cm, where the line splits | (140, 72.5) |
| Brick B1 (orange) | about 6 × 6 cm | (95, 97.5), on the line |
| Brick B2 (orange) | about 6 × 6 cm | (70, 97.5), on the line |
| Barrier | 90 cm long, about 5 cm thick, at least 5 cm tall | x 0 to 90, y 60 to 65 |

The barrier sits between START and END B so robots can't drive straight down to the finish.

## Hints for Students
- **Level 1:** 45° bends are gentle, so good line tracing can follow them. Slow down at the bends if your robot loses the line.
- **Level 2:** Use your colour sensor to spot **yellow**. When you see it, drive forward a little, then turn right 90°.
- **The FORK:** Your robot follows one **edge** of the line. Which edge you follow decides which way the robot goes when the line splits. You can also use the **red** patch as a signal to switch edges or to make a small turn.
- **Level 3:** Spot **green** to know when to stop. On the long path, push the bricks gently. If you go too fast, they may slide off the line.
- **Bonus:** Make your robot play a sound when the colour sensor sees **blue**.

**Make sure everyone understands the rules before the competition starts. Good luck and have fun!**
