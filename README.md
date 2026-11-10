# Heads Up

Heads Up is a small Mac menu-bar app that puts a full-screen alert in
front of you before each meeting on your Google Calendar, with snooze
and a one-click Join. It needs a Mac with Apple silicon (M1 or later)
and macOS 14 or later.

This repository holds only the finished app, its update feed and the
third-party licence notices. Access is by invitation.

## Install

1. **Accept the invitation** to this repository (GitHub emails it, or
   open the repository page while signed in and press **Accept**).
2. **Download** `HeadsUp.dmg` from the latest release:
   [Releases](https://github.com/Eloryo-Developments/heads-up-releases/releases/latest).
3. **Open the DMG and drag Heads Up into Applications.** Then open it
   from Applications. A bell appears in the menu bar, top right.
4. **Sign in with Google.** The Setup Guide opens by itself. Pick the
   Google account whose calendar you want alerts for. Your calendar
   stays between your Mac and Google: nothing is sent anywhere else.
5. **Connect GitHub for automatic updates.** In the guide, press
   **Create a GitHub token**, scroll down, press **Generate token**,
   copy it and paste it into Heads Up. A tick shows when it works. The
   token is kept in your Mac's Keychain. You can skip this and connect
   later in Settings > About.

Google may show "Google hasn't verified this app". That is normal for a
small app: click **Advanced**, then **Go to Heads Up**.

## Updates

Once GitHub is connected, Heads Up checks for updates every 6 hours and
installs them when it relaunches. Updates keep all your settings. If
your access to this repository ends, updates stop; the installed app
keeps working.

## Licences

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
