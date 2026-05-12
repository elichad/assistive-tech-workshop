---
title: Linux (Ubuntu) - Assistive Technology Workshop
layout: default
---

# Assistive Tech Workshop: Linux (Ubuntu)

[Return to main session document](index.md)

1. TOC
{:toc}

<https://documentation.ubuntu.com/desktop/en/latest/how-to/accessibility/>

## Vision

<https://documentation.ubuntu.com/desktop/en/latest/how-to/accessibility/#visual-impairments>

### Colour controls - high contrast mode

Enable: Settings > Accessibility > Seeing > Enable High Constrast 

Explore: Look for visual changes in the images, links, and buttons - some will change, some will stay the same

Report: any element that is not obviously distinguishable from nearby elements or the background

Disable: Settings > Accessibility > Seeing > Disable High Constrast 

### Magnifier

Enable: Settings > Accessibility > Zoom > Enable Desktop Zoom. You can change the magnification factor, the mouse tracking, and the position of the magnified view on the screen.

Explore: Navigate to the "Enable federation" page under the "Pillars" heading on the TREvolution homepage.

Report: Is it particularly difficult to find anything on the page?

Disable: Settings > Accessibility > Zoom > Disable Desktop Zoom.

### Orca (screen reader)

Rerequires 10-15 mins to explore. 
<https://documentation.ubuntu.com/desktop/en/latest/how-to/accessibility/orca/read-screen-aloud/>

Enable: Settings > Accessibility > Seeing > Enable Screen Reader 

Explore: Navigate to website using the keyboard and the screen reader output. Check Orca preferences here <https://documentation.ubuntu.com/desktop/en/latest/reference/accessibility/orca-preferences/>

Report: Is it particularly difficult to find anything on the page?

Disable: Settings > Accessibility > Seeing > Disable Screen Reader

Cheat sheet: <https://github.com/C-Loftus/orca-intro-guide/blob/main/cheatsheet.md>

### Other

* Adjust text size (Settings > Accessibility > Seeing > Enable Large Text)
* Adjust cursor size (Settings > Accessibility > Seeing > Cursor size : choose a size)
* Beep when Num Lock or Caps Lock are turned on or off (Settings > Accessibility > Seeing > Enable Sound Keys)

<div style="page-break-after: always;"></div>

## Hearing

<https://documentation.ubuntu.com/desktop/en/latest/how-to/accessibility/#hearing-impairments>

### Display audio alerts visually

Enable: Settings  > Accessibility > Hearing > Enable Visual Alerts

Explore: Make an audio notification happen. Ways that might work:

* get someone to send you an email
* get someone to send you a message on Slack/Teams/etc
* test Flash in Settings  > Accessibility > Hearing
Choose between flasing entire screen or window.

Report: N/A

Disable: Settings  > Accessibility > Hearing > Disable Visual Alerts

### Other

* Allow volume to exeed 100% (Settings > Accessibility > Hearing > Enable Overamplification)

<div style="page-break-after: always;"></div>

## Mobility

<https://documentation.ubuntu.com/desktop/en/latest/how-to/accessibility/#mobility-impairments>

### Mouse/Touchpad Pointer Speed

Enable: 

* Mouse: Settings > mouse & touchpad > Mouse > Adjust the Pointer Speed. Scroll direction and primary button can be configure in this section
* Touchpad: Settings > mouse & touchpad > Touchpad > Adjust the Pointer Speed. Scroll direction and Clicking can be configure in this section

Explore: Does any particular setting feels more easy?

Disable: 

* Mouse: Settings > mouse & touchpad > Mouse > undo chanches.
* Touchpad: Settings > mouse & touchpad > Touchpad > undo chanches.

### Pointing and Clicking

Enable:  Settings > Accessibility > Pointing and Clicking >

* > Enable Mouse Keys to move mouse pointer with the numeric keypad
* > Enable Locate Pointer to locate pointer with Left Ctrl.


Explore: does moving the mouse pointer with the numeric keypad work in every window/screen?

Disable: Settings > Accessibility > Pointing and Clicking > and disamble any option that was activated. 

### On-screen keyboard / touch keyboard

Enable:  Settings > Accessibility > Typing > enable Screen keyboard

Explore: type into the search box using the on-screen keyboard

Report: if typing with the on-screen keyboard doesn't work in a text box

Disable: Settings > Accessibility > Typing > disable Screen keyboard

### Other

* Use secondary click by honding down the primary mouse button (Settings > Accessibility > Pointing and Clicking > Enable Simulated Secondary Click)
* Sticky, repeat, slow and bounce keys (Settings > Accessibility > Typing > Typing Assit section)

<div style="page-break-after: always;"></div>

## Cognitive

### Minimise animation effects

Enable: Settings > Accessibility > Seeing > enable Reduce Animation

Explore: 

* Subtle differences when you minimise/maximise/change size of windows.
* Effect on browser - click "Pillars" before turning the setting off and see how the scroll down the page is animated. Does this change when you change the setting?
* Example: <https://www.w3.org/WAI/WCAG21/working-examples/css-reduced-motion-query/>

Report: 

* if animations are unchanged after turning the setting off

Disable: Settings > Accessibility > Seeing > disable Reduce Animation

Bonus: This has its own setting in most browsers - `prefers-reduced-motion` <https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/At-rules/@media/prefers-reduced-motion>. You can check if a user has this preference set using CSS.

### Other

* Notification settings (Settings > Notifications > App Notifications)
* Focus mode (Settings > Notifications > Enable Do not Disturb)

## Additional resources

<https://documentation.ubuntu.com/desktop/en/latest/how-to/accessibility/>
