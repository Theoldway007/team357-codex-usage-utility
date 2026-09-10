# Privacy

Team 357 Codex Usage Utility is designed to keep account and computer readings on the user's computer.

## Information the utility reads

- Account identity, weekly allowance, reset time, and optional token activity supplied by the installed Codex helper
- CPU time, physical memory totals, GPU counters, ready drive labels and capacity
- Supported temperatures through installed system or hardware-vendor interfaces

The utility does not read conversation text, prompts, browser cookies, saved passwords, document contents, screenshots, or drive contents. It does not copy Codex authentication files.

## Information sent over the network

Team 357 does not receive account readings, allowance percentages, token totals, hardware readings, or drive information.

A manual update check requests a small platform-specific release manifest from `team357.com` over HTTPS. A manual update download requests the versioned package from that same fixed origin. The web host receives ordinary request information such as IP address, user agent, and requested filename. No background update service or silent installation is used.

Codex itself communicates with OpenAI under the user's existing Codex session. OpenAI's terms and privacy practices apply to that service.

## Local storage

The utility keeps preferences and a small local usage-history file. History stores observation time, percentage, reset time, and a short hash used to separate account histories. It is limited to 14 days and 4,096 readings. Raw email addresses, passwords, authentication tokens, conversation content, and hardware readings are not stored in history.

Windows may keep one verified installer and one partial file in the utility's update cache. Mac may keep one bounded candidate in its update cache. Old owned cache files expire after 14 days while the utility runs. The Windows edition overwrites one bounded local diagnostic error file and removes it after 14 days; it is never uploaded automatically.

## Hardware access

Drive monitoring enumerates volume roots and capacity, not file contents. On Windows, clicking a drive opens its root in File Explorer after checking readiness. The utility installs no hardware driver, service, browser extension, firewall rule, or antivirus exception, and it does not require administrator access.

## Sharing

Share controls use fixed promotional text and the public Team 357 Utility Lab link. They do not include live account readings, computer readings, screenshots, or identifiers. The user chooses and sends through the selected destination.

## Removal

Uninstall keeps preferences and history by default. The separate full-removal option deletes the utility's owned preferences, history, and cache. It does not remove Codex, its sign-in, or unrelated files.

Last updated: September 10, 2026.

