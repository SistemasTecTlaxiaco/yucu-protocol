
# Mobile UX Testing – Yucu Protocol Demo

**Date:** November 19, 2026  
**Device:** Samsung Galaxy A56  
**Operating System:** Android  
**Browser:** Not recorded  
**Network Connection:** Not recorded

## 1. Initial Loading

**Result: Acceptable, with observations.**

The website loads and responds relatively well on the mobile device. However, during the initial loading process, some text appears excessively large over images or logos. This text covers part of the screen and makes the content harder to view.

## 2. Text Readability

**Result: Passed.**

The text is readable on the mobile screen without requiring zoom.

## 3. Button Functionality

**Result: Passed.**

Buttons respond immediately when tapped. There is no need to press them multiple times.

## 4. Chat Functionality

**Result: Passed during opening.**

The chat opens correctly during the tests. No obvious errors were observed when opening it.

## 5. Offline Functionality

**Result: Website inaccessible.**

After enabling airplane mode and attempting to access the website, the browser displays a message indicating that the site cannot be reached.

## 6. Screen Orientation

**Result: Passed, with minor observations.**

When rotating the phone from portrait to landscape mode, the interface maintains its structure. After returning to portrait mode, some text takes a moment to adjust. The oversized text observed over images disappears shortly afterward.

## 7. Weak Network Connection

**Result: Issues detected.**

When the internet connection becomes weak:

- The application responds slowly.
- Some elements take longer to load correctly.
- Oversized text appears and covers part of the screen.
- The overall viewing experience becomes less comfortable.

## 8. Identified Issues

1. Oversized text appears over images or logos during interface loading.
2. Slow performance and display problems occur when the internet connection is weak.

## 9. Conclusion

The Yucu Protocol demo generally performs well on a Samsung Galaxy A56. Text is readable, buttons respond correctly, and the interface maintains its structure when changing screen orientation.

However, improvements are needed in text positioning over visual elements and application performance under weak network conditions.

These results are based exclusively on the tests performed using the device described above.
