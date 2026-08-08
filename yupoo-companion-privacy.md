# Privacy Policy — Yupoo Companion

_Last updated: 7 August 2026_

Yupoo Companion is a browser extension that changes how Yupoo (yupoo.com)
catalog pages look and behave. This policy explains exactly what it stores.

## Summary

**Yupoo Companion does not collect, transmit, or sell any data.** Everything it
saves stays in your own browser, on your own device. There is no account, no
server, and no analytics.

## What is stored, and where

All of the following is kept locally using the browser's `chrome.storage.local`
API. None of it is ever sent anywhere.

| Data | Why |
| --- | --- |
| Display preferences (image size, spacing, colors, dark mode, hidden elements, custom CSS) | To keep your settings between visits |
| Named presets | So you can save and re-apply combinations of the above |
| Starred items — for each item you star, its album address, the album title, and the address of its thumbnail image | To show that item again on the Favorites page |
| Notes and tags you type onto starred items | To let you annotate and organise what you saved |
| Shop access codes | So password-protected Yupoo shops can be unlocked without retyping the code |
| Link-converter preference | To remember which shopping agent you prefer |

### About shop access codes

Some Yupoo shops are protected by an access code supplied by the seller. If you
choose to save one, it is stored locally so the extension can fill it in for
you. These codes are stored **unencrypted** in your browser profile, in the same
way a browser stores form data.

Please do not enter anything here that protects a real account. These fields are
intended only for shop access codes handed out by sellers.

### About starred items

Starring an item saves a pointer to it — the album's address, its title and its
thumbnail's address — so the Favorites page can show it to you later. Only items
you explicitly star are saved. The extension does not keep a record of the pages
you visit, and nothing is saved unless you click the star.

## Data we do NOT handle

- No personal information is collected.
- No record of pages you have visited is kept.
- No browsing history is recorded or transmitted.
- No data is sold or shared with third parties.
- No analytics, telemetry, or tracking of any kind.
- The extension does not read or store passwords for any account.

## Permissions

- **storage** — saves the preferences listed above on your device.
- **scripting** — registers the link converter on other sites, only after you
  explicitly enable that option.
- **declarativeNetRequestWithHostAccess** — attaches a Referer header to image
  requests made to Yupoo's own image server, so saved thumbnails display. It
  does not observe or log any request.
- **Access to yupoo.com** — required to restyle Yupoo pages.
- **Optional access to all sites** — not granted on install. Requested only if
  you turn on "Also convert on other sites", and used solely to rewrite
  marketplace links on pages you visit. Turning the option off revokes it.

## Affiliate links

When the link converter is enabled, converted links include the developer's
referral code. This does not change the price you pay; the shopping agent pays a
small commission on orders placed through them. The converter is off by default
and can be switched off at any time in the extension's popup.

## Removing your data

Uninstalling the extension deletes everything it has stored. You can also clear
individual items from the extension's popup or favorites page at any time.

## Contact

Questions about this policy: https://ko-fi.com/tanukitech
