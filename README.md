# TimeCapsule
*A letter to your future self*

TimeCapsule is a small, single-page website where you write a note to your future self, choose a date, and seal it away. The note stays locked until that date arrives. Everything runs in the browser, with no account and no server.

## Features

- **Create capsules** - Give a capsule a title (up to 70 characters), a message (up to 5,000 characters), an unlock date, and an optional feeling.
- **Sealed until the date** - A capsule cannot be read before its unlock date. The card shows how many days are left.
- **Your library** - See all capsules at a glance, filter by All, Locked or Unlocked, read unlocked notes, or delete any capsule.
- **Live statistics** - Counters show the total number of capsules, how many are still waiting, and how many are ready to open.
- **Light and dark mode** - A switch in the header slides between light and dark. The knob shows a sun in light mode and a moon in dark mode. On a first visit the site follows your device setting.
- **Colour themes** - The three-dots button next to the switch opens a small panel with Default plus pastel green, blue, red and violet. Tapping a colour recolours the whole page. Every colour works in both light and dark mode.
- **Remembers your choices** - Your capsules, light or dark mode, and colour theme are saved in your browser.

## Getting started

1. Open index.html in any modern browser (double-click the file).
2. Tap Create your first capsule, or scroll to the form.
3. Write a title and message, pick an unlock date, and choose how you feel.
4. Tap Seal capsule. It appears in Your capsules.
5. Come back on or after the unlock date and tap Read note.

## Changing the theme

| Action | How |
| --- | --- |
| Light / dark | Tap the switch in the header. |
| Change colour | Tap the three dots next to the switch, then tap a colour. |
| Return to the original look | Open the three-dots panel and tap Default. |

## Files

- `index.html` - The whole website: HTML, CSS and JavaScript in one file. No build step or dependencies.

## Good to know

- Capsules are stored in your browser (localStorage) on this device only. They are not uploaded anywhere and do not sync between devices or browsers.
- Clearing your browser data, or using private browsing, will remove saved capsules. Keep a copy of anything important.
- The unlock date is checked against your device clock.
