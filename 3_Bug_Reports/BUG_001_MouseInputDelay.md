# Bug Report #001: Initial Mouse Input Delay

**Date:** 2024-01-22
**Game:** Chronigma
**Build:** (Уточнить, если известно, иначе - Steam public build as of 2024-01-22)
**Platform:** PC (Windows 11)
**Hardware:** ROG Zephyrus G16 (i9-13900H, NVIDIA GeForce RTX)
**Severity:** Medium
**Priority:** Medium
**Status:** Open

**Summary:**
Mouse input is not registered during the first ~70 seconds after launching the game and reaching the main menu/starting gameplay.

**Description:**
Upon launching the game and starting a new game, the mouse cursor is visible but does not interact with the UI (e.g., cannot click "Continue" or "Options"). Player is forced to use keyboard navigation. Full mouse functionality (menu interaction, camera control in-game) restores spontaneously approximately 1 minute and 9 seconds after the game process starts.

**Steps to Reproduce:**
1. Launch Chronigma from Steam.
2. Wait for the main menu to load.
3. Immediately attempt to use the mouse to click any menu button (e.g., "New Game").
4. Observe the lack of response.

**Expected Result:**
Mouse input should be available immediately upon reaching any interactive menu or gameplay.

**Actual Result:**
Mouse input is delayed by approximately 70 seconds.

**Evidence:**
- Video: `Gameplay_Videos/Log_1_mouse.mp4` (See timestamp 01:09:11)
- Screenshot: (Optional, of unclickable menu)

**Additional Notes:**
Issue occurred on a fresh launch. Not tested after rebooting the game within the same session.