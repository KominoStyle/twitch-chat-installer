# Changelog

## 0.3.30 — 2026-10-16

A more reliable Twitch sign-in, clearer updates and easier access to feedback.

## New
- **Help & feedback** Report a bug, request a feature or suggest an improvement from General or the Feedback menu at the bottom right. The selected GitHub form opens in your browser.
- **Status Font size** Set a separate size for Twitch status, error and moderation notices, or keep them matched to message text. The related controls share one compact group with help at the info icon.

## Improved
- **A focused Twitch sign-in** Sign-in opens near Settings and remains reachable above it. Login, authenticator steps and confirmation share a centered layout and one window size. Successful sign-in returns you to the selected chat without showing the Twitch homepage.
- **Chat above Settings** Your chat remains above the Settings menu. The chat's Always on top choice continues to control its position relative to other apps.
- **Readable release notes** A quiet Release notes button opens a centered reading window with clear headings and grouped changes. Updates include the notes for versions you skip.
- **A compact update screen** Updates show the app logo, target version and progress in a dedicated compact window.
- **Lighter update checks** Version checks and change history load from the public GitHub repository. App update packages continue through the download service with signature verification.
- **More compatible settings** Extra fields from newer versions no longer prevent startup and remain saved when you change another setting. Invalid values in known settings still report an error.

## Fixed
- **Keep chat in its channel** Chat stays on the selected channel. Supported Twitch popups retain their own surface, and external webpages open in your Windows default browser. Pending Twitch menu actions that are not integrated into the app are hidden.
- **Reliable text selection** Dragging a selection from a channel or window-size field across the layer illustration preserves the selection.
- **Moderation layout** Native moderation buttons align with their message as text size changes. This changes their layout; Twitch still handles each moderation action.
- **One font-size control** The redundant Twitch Font Size row is hidden. Its menu previews use Twitch Default while message, input and status sizes remain under the app's controls.
- **Mod icons start off once** This update turns Show Mod Icons off once. Your later choice is remembered, and Show Moderation Actions keeps its existing setting.
- **Cursor recovery after sign-in** A targeted Windows cursor recovery runs after the sign-in window closes, preserving normal cursor handling during use.

## 0.3.23 — 2026-10-15

Twitch Chat for Windows x64.

- Original Twitch chat in a transparent desktop window, with adjustable colors, text and window behavior.
- Twitch, BetterTTV, FrankerFaceZ and 7TV emotes with inline Tab completion and chat input history.
- Separate message and input font sizes, with compact, centered input emotes.
- Updates in General, with download progress, verification and an explicit Install and restart action.

New installations start without a selected channel. Enter one in General and sign in to Twitch to open chat. Updates preserve your settings and Twitch sign-in.
