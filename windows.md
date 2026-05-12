---
title: Windows
layout: default
---

# Assistive Technology Workshop: Windows

[Return to main session document](index.md)

1. TOC
{:toc}

## Vision

### Colour controls - high contrast mode
Enable: Settings > Accessibility > Contrast themes > (select a theme) > Apply 

Explore: Look for visual changes in the images, links, and buttons - some will change, some will stay the same

Report: any element that is not obviously distinguishable from nearby elements or the background

Disable: Settings > Accessibility > Contrast themes > select "None" > Apply

### Magnifier

Enable: Start > search "Magnifier" > launch. Once open, click the plus sign + in the Magnifier toolbar to set the zoom level.

Explore: Navigate to the "Enable federation" page under the "Pillars" heading on the TREvolution homepage.

Report: Is it particularly difficult to find anything on the page?

Disable: Close the Magnifier toolbar. It is usually in the top left region of the screen. You can press Ctrl + Alt + - (minus) to reset the zoom level.

### Narrator (screen reader)

*Allow 10+ minutes to explore the Narrator tool. Please use headphones!*

*Warning: if you are prone to sensory overload from overlapping conversations, be aware that using Narrator during a busy workshop may cause similar effects due to its constant spoken feedback.*

Enable: Start > search "Narrator" > launch Narrator

Explore: 

* Follow the QuickStart tutorial in the Narrator Home app (should appear when you launch Narrator)
* Try to find Alex and Eli on the TREvolution website using only the keyboard and screen meter announcements
    * go to< https://dareuk.org.uk/trevolution/>
    * on the homepage there is a link to the list of teams
    * each team has a list of members (Alex and Eli are from the University of Manchester)
* Cheat sheet: <https://dequeuniversity.com/screenreaders/narrator-keyboard-shortcuts>

Report: 

* any element that isn't announced usefully. The name of a heading/link/button should be descriptive enough to understand it even if you jumped to it from somewhere else on the page.
* any element you can see on the page but can't reach with a keyboard

Disable: Windows key + Ctrl + Enter


### Other

* Adjust text size (Settings > Accessibility > Text size)
* Adjust display scale (Settings > System > Display > Scale)
* Mouse pointer style settings (Settings > Accessibility > Mouse pointer and touch)
* Colour filters for accommodating colourblindness (Settings > Accessibility > Colour filters)
* <https://www.microsoft.com/en-us/windows/accessibility-features#vision>

<div style="page-break-after: always;"></div>

## Hearing

### Live captions

Enable: Settings > Accessibility > Captions > turn on Live captions. Then select "yes, continue" when the live captioning bar appears (top of screen) to allow download of language files & local caption processing.

Explore: 

* Play the video on the TREvolution homepage <https://dareuk.org.uk/trevolution/>. Leave it playing and switch tabs/windows. 
* Customise the captions with the settings in the captions bar (gear icon) and Settings > Accessibility > Captions > Caption style.

Report: N/A

Disable: Close the caption bar, or go to Settings > Accessibility > Captions > Live captions

### Display audio alerts visually

Enable: Settings  > Accessibility > Audio > Flash my screen during audio notifications

Explore: Make an audio notification happen. Ways that might work:

* get someone to send you an email
* get someone to send you a message on Slack/Teams/etc
* trigger a notifcation sound on demand - Control Panel > Hardware and Sound > Change system sounds > select an event and click Test

Report: N/A

Disable: Settings  > Accessibility > Audio > Flash my screen during audio notifications

### Other

* Mono audio (Settings > Accessibility > Mono audio)

<div style="page-break-after: always;"></div>

## Mobility

### On-screen keyboard / touch keyboard

Enable: Settings > Accessibility > Keyboard > On-screen keyboard

Explore: type into the search box using the on-screen keyboard

Report: if typing with the on-screen keyboard doesn't work in a text box

Disable: Close the keyboard window

### Sticky, filter, and toggle keys 

Enable: Settings > Accessibility > Keyboard > Sticky keys / Filter keys / Toggle keys (and sub-settings)

Explore: 

* enable one or more of the settings & explore their sub-settings
* try actions like Ctrl-C and Ctrl-V (copy & paste)
* note that Sticky keys may automatically turn off when two keys are pressed at the same time - can disable this in the Sticky keys sub-settings

Report: if the website doesn't handle the modified keystrokes the same as the normal keystrokes

Disable: Settings > Accessibility > Keyboard > Sticky keys / Filter keys / Toggle keys

### Other

* Voice access & voice typing (requires quiet room to work effectively, Settings > Accessibility > Speech > Voice access, chat to Eli to learn more!)
* Eye tracking (requires specialised hardware, chat to Eli to learn more!)
* Mouse keys (requires numpad, Settings > Accessibility > Mouse > Mouse keys (under Interaction))
* Touch gesture settings (screen/touchpad)
    * trackpad: Settings > Bluetooth & devices > Touchpad
    * touchscreen: Settings > Bluetooth & devices > Touch

<div style="page-break-after: always;"></div>

## Cognitive

### Minimise animation effects

Enable: Settings > Accessibility > Visual effects > Animation effects (turn off)

Explore: 

* Subtle differences when you minimise/maximise/change size of windows.
* Effect on browser - click "Pillars" before turning the setting off and see how the scroll down the page is animated. Does this change when you change the setting?
* Example: <https://www.w3.org/WAI/WCAG21/working-examples/css-reduced-motion-query/>

Report: 
* if animations are unchanged after turning the setting off

Disable: Settings > Accessibility > Visual effects > Animation effects (turn on)

Bonus: This has its own setting in most browsers - `prefers-reduced-motion` <https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/At-rules/@media/prefers-reduced-motion>. You can check if a user has this preference set using CSS.

### Immersive Reader (Edge)

Enable: visit any website (e.g. <https://dareuk.org.uk/trevolution/>) in Microsoft Edge. Click "Immersive Reader" or "More actions" > "Immersive Reader" in the address bar (next to the "Add to Favourites" star).

Explore: 

* Scroll through the page and compare the content to the non-reader mode.
* customize the view using the settings in the Immersive Reader toolbar
* try the "Read aloud" setting

Report: if content is not visible when using the Immersive Reader

Disable: close the Immersive Reader toolbar

### Other

* Make notifications stick around longer (Settings  > Accessibility > Visual effects > Dismiss notifications after this amount of time)
* Customise taskbar (Settings  > Personalization > Taskbar)
* Notification settings (Settings  > System  > Notifications)
* Focus mode (temporarily block notifications, sounds, and alerts) ( Settings > System > Focus)
* Text suggestions (Settings > Time and language > Typing > Show text suggestions when typing on the physical keyboard)

## Additional resources

* <https://www.microsoft.com/en-us/accessibility>
* <https://support.microsoft.com/en-gb/windows/discover-windows-accessibility-features-8b1068e6-d3b8-4ba8-b027-133dd8911df9#PickTab=Windows_11&WindowsVersion=Windows_11&windowsversion=windows_11>
