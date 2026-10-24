# TypePilot Privacy Policy

**Last updated:** October 24, 2026

TypePilot is a Chrome extension that expands typed shortcuts (for example `/reply`) into text snippets you create. This policy explains what the extension accesses and what happens to it.

## Summary

TypePilot does not collect, sell, or transmit your data. It has no servers, accounts, analytics, ads, or third-party trackers. Everything it stores stays in your browser.

## What TypePilot accesses and why

| What | Why | Leaves your device? |
| --- | --- | --- |
| Text you type into fields on web pages | To recognize when you type one of your snippet triggers. Typed text is checked in memory and is not stored or logged. | No |
| Your snippets and folders | To show, edit, and insert them. Stored with `chrome.storage.local`. | No |
| Sites you pause | To stop typed triggers from expanding on the sites you choose. Only the site name (for example `app.slack.com`) is saved, never the page address or its content. Stored with `chrome.storage.local`. | No |
| How often you use each snippet | To list your most-used snippets first. For each snippet, only a count and the time it was last inserted are saved, never where you used it or what you typed. Stored with `chrome.storage.local`. | No |
| Copies of your snippet library | So you can restore your snippets after a mistake. Up to five copies of your snippets and folders (at most one a day, taken when they changed) and one from before your last overwrite import or restore. Stored with `chrome.storage.local`. | No |
| When you last exported | To remind you to export a backup file. Only the time of your last full export and of the last time you dismissed the reminder are saved. Stored with `chrome.storage.local`. | No |
| Display preferences | To remember your theme choice and whether you dismissed the popup tip. Stored in the browser's `localStorage` on this device. | No |
| Your clipboard | Used only while you insert a snippet: read when the snippet contains the `{clipboard}` command, and written then pasted when an editor blocks other insertion methods. In that case the inserted snippet text may remain on your clipboard. Clipboard contents are never stored. | No |
| Tab and page address (URL) | To decide whether the current tab is a normal web page you can insert into, to handle Outlook on the web, to show and pause the current site in the popup, and for the `{site}` and `{url}` commands you put in your own snippets. | No |
| Files you choose to import | Read once to import snippets. | No |

## Network requests

TypePilot makes no network requests of its own. Text you insert into a web page becomes part of that page, just like text you typed by hand, and is handled by that website under its own privacy policy.

## Data retention and deletion

Your snippets stay in your browser until you delete them or uninstall TypePilot. A snippet's usage count is removed some time after you delete the snippet, and a deleted snippet stays in the saved copies of your library until newer copies replace them. Uninstalling the extension removes all of its stored data. You can export your snippets as a JSON file at any time from the popup or dashboard.

When you replace your library with an overwrite import or by restoring a copy, TypePilot keeps one safety copy of your previous snippets and folders on your device. That copy is not affected by later edits or deletions. It stays until a later overwrite import or restore replaces or removes it, or until you uninstall TypePilot. The up to five daily copies stay until newer copies replace them; if you delete all your snippets, no new copies are taken, so the existing ones stay until you uninstall TypePilot. None of these copies is ever sent anywhere.

## Sharing

TypePilot does not share data with anyone. We do not sell data or use it for advertising, credit decisions, or any purpose unrelated to the extension's single purpose of text expansion.

## Children

TypePilot is not directed at children under 13 and does not knowingly collect information from anyone.

## Changes

If this policy changes, the "Last updated" date above will change. Any future feature that sends data off your device will be opt-in and described here before it ships.

## Contact

Questions about this policy: [hos.gouda90@gmail.com](mailto:hos.gouda90@gmail.com)
