# Trapezoid Tabs For Firefox
I loved the trapezoid tabs like in old Chrome, and now with Firefox Nova (Firefox's new design that features ovals everywhere), they are even more helpful to distinguish tabs from all the other UI elements at a glance.

Works best with compact mode enabled in Firefox's Main menu > Settings > Appearance > Website appearance. so I decided to make my own userChrome based on https://github.com/HolyPolyRoly/TrapezoidTabsForFX.

Preview:
<img width="1364" height="225" alt="image" src="https://github.com/user-attachments/assets/f6f344d0-81b8-489b-bcef-dad20a00ef91" />

## Installation
1. Paste the code from userChrome.css into your userChrome.css; for Windows, this is found in `%APPDATA%\Mozilla\Firefox\Profiles\[your-default-release]\chrome\`
2. In Firefox `about:config`, set `devtools.chrome.enabled` to true.
3. Restart Firefox.
4. Optional: This works best with *compact mode* enabled in Firefox's Main menu > Settings > Appearance > Website appearance.

Works best with Nova (the default in Firefox 157 and later).  
Works best with compact mode enabled in Firefox's Main menu > Settings > Appearance > Website appearance.

## What's new and credit due
This is based on https://github.com/HolyPolyRoly/TrapezoidTabsForFX.  Changes from that version:
- Tabs overlap better
- A bold border and white tab color offset the active tab very starkly.  Inactive tabs show as light gray, making it more obvious.
- Some extra spacing is removed for a more
- Tab bar moved to top of window (since the address bar and bookmarks apply only to the current tab, it is a better mental model that the tab includes them)

### Ideas for the future
- Dark mode
- Incorporate colors from theme or settings
