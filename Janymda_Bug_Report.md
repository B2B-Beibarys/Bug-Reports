# Bug Report: Predictable "Super Question" in Movies and Music Quiz

**Environment:** 
- **OS:** Android 16 (OneUi 8.0)
- **Device:** Samsung Galaxy A16
- **App Version:** 8.13.0
- **Product:** Janymda App (Beeline)

**Type:** Logic Vulnerability / Game Mechanics Issue
**Severity:** Major (Loss of business value/resources)
**Priority:** High

## Description
The "Super Question" does not rotate upon subsequent attempts. This allows users to guarantee a win (1 GB prize) by simply remembering the correct answer from a failed first attempt and reusing it in the second attempt.

## Steps to Reproduce
1. Launch the **"Movies and Music"** game.
2. Progress through the quiz until you reach the **"Super Question"** stage.
3. Select any answer. If incorrect, remember or screenshot the correct answer.
4. Use a second attempt (restart the game/re-entry).
5. Reach the "Super Question" stage again.

## Expected vs Actual Result
**Actual Result:** The system presents the exact same "Super Question" as the previous attempt. The user already knows the correct answer, making the prize guaranteed.

**Expected Result:** The "Super Question" should be pulled randomly from a pool of questions for every new attempt to ensure fairness and prevent resource abuse.
