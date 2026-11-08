# Chutku

**A free voice assistant for your Windows PC.** Say what you want in English, Hindi or Hinglish, and Chutku does it
for you, then tells you honestly what happened.

- "Spotify pe lofi chalao"
- "meri last PDF kholo"
- "D drive mein kitni jagah hai"
- "har roz 8 baje weather batao"
- "Rahul ko WhatsApp pe hi bhejo"

## What Chutku can do

- **Apps and windows:** open, close and switch apps; arrange windows; control Spotify, VLC, Telegram, VS Code,
  File Explorer, Settings, Notepad and more.
- **Files:** find any file by name, open your latest PDF or photo, tidy your Downloads. Every change can be undone.
- **Web:** search, news, weather, YouTube.
- **Your PC:** volume, brightness, battery, disk space, screenshots.
- **Screen:** "what's on my screen?", "click the first video".
- **Messages:** WhatsApp and Telegram. She always asks before sending to someone new.
- **Reminders and automations:** "30 min baad yaad dilana", "har roz 8 baje briefing".
- **Routines and teaching:** one phrase runs several steps; show her a task once and she learns it.
- **Your phone:** chat, talk and approve from your phone (optional).

## Download and install

1. Go to **[Releases](../../releases/latest)** and download **ChutkuSetup.exe**.
2. Double-click it. If Windows shows **"Windows protected your PC"**, click **More info**, then **Run anyway**. This
   appears because the setup is not signed with a paid certificate; the download is checked against a pinned
   checksum before anything is installed.
3. Click **Install**. The defaults are already right (Chutku starts when you sign in, and a desktop shortcut is
   made). No administrator rights are needed. The setup downloads the app (about 220 MB), checks it, and opens
   Chutku.

Needs Windows 10 or 11 (64-bit) and about 1 GB of free space, plus a microphone for voice.

## First start

Chutku opens a short setup page. Only the first step matters; everything else already has a good default.

1. **A free AI key** (one minute): press **Get a free key**, sign in with Google, press **Create API Key**, copy it
   and paste it into the box. You don't choose a provider: Chutku recognises the key. It is stored in Windows
   Credential Manager, never in a file.
2. Press **Start using Chutku**. Anything you typed on the page is saved.

Everything else on that page is optional and can be changed any time under **Settings**: your name, her name and
voice, how much she does without asking (Safe by default: she opens and looks at things by herself and asks
before any change), a microphone test, offline packs, and websites she should use while signed in.

**Your phone (optional):** press **Connect my phone** (Settings or the Phone page). It installs Tailscale if needed
(press **Yes** if Windows asks), opens its sign-in page, turns phone access on and shows a code. On the phone,
install the free Tailscale app, sign in with the same account, scan the code and choose a PIN.

**Telegram and "after a restart" (optional):** on the Phone page, the **Telegram** card walks you through making a
bot with @BotFather (paste its token, then scan a code to pair). **Reach this laptop after a restart** then sends
"Laptop is ON" to your Telegram after every restart, with a link that shows the Windows sign-in screen on your
phone so you can sign in from anywhere. It asks Windows for permission once.

Then press **Ctrl+Alt+Space** in any app and talk, or type in the Chutku window. Try:

- "what can you do?"
- "kitni jagah bachi hai"
- "open notepad"
- "aaj ki news"

**Ctrl+Alt+F12** stops everything at once. The full guide is under **Help** in the Chutku window.

## Privacy and safety, in plain words

- **Your things stay on your PC.** Files, screen text, clipboard and memory stay on your PC. With an AI key, only
  your request and public results go to that service.
- **She asks before anything serious.** Deleting, sending messages, running programs, and shutting down or
  restarting always wait for your OK.
- **Deleted files go to the Recycle Bin.** You can bring them back.
- **System folders are never touched.** Chutku never runs as administrator and never changes Windows or program
  folders. (Only the optional "after a restart" setup asks Windows once, when you press it.)
- **Every step is checked,** and she tells you exactly how many steps really worked.
- **Web pages and messages can't give her orders.** Text she reads cannot tell her what to do.
- **The phone link is end-to-end encrypted.**

## Uninstall

If you turned on "Reach this laptop after a restart", press **Turn off** on the Phone page first. Then Windows
**Settings → Apps → Chutku → Uninstall**. It asks whether to delete your data (memory, settings, history) as well.
Say no to keep it for later.

## Questions and problems

| Question or problem | Answer |
|---|---|
| Is it free? | Yes. The AI keys from Groq and Google AI Studio are free too, with daily limits. |
| Does it work offline? | Yes, after you download the offline packs in Settings. It is faster with a graphics card. |
| The shortcut key does nothing | Another app uses Ctrl+Alt+Space. Close it, or restart Chutku. |
| "quota" or "busy" | The free AI limit is used up for now. Wait a bit, or add a key for the other service in Settings. |
| She says actions are paused | Click **Resume actions** in the Chutku window, or say "resume". |
| Something seems broken | Say "apna checkup karo". She checks herself and repairs what she can. |
| Can I use it commercially? | No. Some bundled voice models are licensed for non-commercial use only (see NOTICE in the app folder). |
