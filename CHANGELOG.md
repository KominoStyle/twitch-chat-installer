# Changelog

## 0.4.20 — 2026-11-10

GuideMe, a new Chat tools layer and more control over how you read and use Twitch Chat.

## New
- **GuideMe** A nine-step Quick Guide, an interactive Settings explorer, illustrated instructions and troubleshooting help are available from General and the Feedback menu. What's new shows the changes in your installed public version.
- **Chat tools** Find replies, threads, reading direction, alternating backgrounds, deleted messages, highlights, sounds and automatic actions in one layer.
- **Your own message highlights** Match words, sender names or Twitch badges. Choose colors, sounds and separate channel exceptions, manage rules and use your own short imported notification sounds.
- **Deleted messages** Choose Twitch's normal behavior, hide deleted rows, or keep and highlight messages that this app already received. Choose text or full-line highlighting.
- **New message sound** Get a separate notification for new messages in your own channel, with its own volume and minimum interval. Your own messages and native Bot-badged messages are excluded.
- **Automatic Raid participation** Choose destination channels with a Blacklist or Whitelist. A Raid from your open Chat minimizes the original Chat and opens the destination at the same position. Later Raids reuse that temporary Chat; Close Chat closes both.
- **Automatic claims** Use the original available Bonus Channel Points and earned Drops claim actions while Chat is open.
- **Windows startup** Choose whether the app opens when Windows starts, independently of opening Chat when the app starts.
- **User cards** See public account details, LIVE status and a paused preview for channels confirmed live.

## Improved
- **Settings beside your Chat** Move Settings by its header and pin it to keep it open when clicking elsewhere. Window layout controls, saved positions and Click-Through work together more consistently.
- **Readable text** Additional sizes cover replies, rewards, subscription and other event notices. Match message size while retaining the last independent value, and keep the message input at its own size.
- **Color controls** Share useful text and highlight colors, reuse background combinations and use the Color picker.
- **Emotes and emojis** Inspect larger previews and original emote details, search the emote menu, reuse recent choices and complete emotes or usernames with Tab.
- **Reading conversations** Open a thread without replying, choose newer messages at the top and separate ordinary neighboring messages with alternating backgrounds.
- **Media previews** Shared playback and volume controls, refreshed media when resuming and improved handling when a live preview falls behind.
- **Update history** Read public release history and open an eligible older version separately from the notes for an offered update. History loads on demand and preserves the place you are reading.

## Fixed
- **Transparent notices** Subscription, reward, status and other message notice backgrounds follow Chat's opacity and Click-Through while preserving their colors and readable text.
- **Twitch panels** Hiding the leaderboard preserves polls and other shared community events. Raid and Hype Train displays retain their independent behavior.
- **Chat and input details** Improved text and emote alignment, reply presentation, emote previews, input completion and public account details.
- **Reliable controls** Settings keep focus and current edits during background saves; hidden-frame movement, window controls, update handling and supported Twitch navigation receive further fixes.

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
