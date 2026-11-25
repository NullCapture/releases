# Changelog

What changed in each version of Privacy AI Assistant.

## November 25, 2026

**2.1.2**

### Improved

* Added an Install update option to the assistant bar's menu when a new version is ready.
* Changed installing an update to show that the download is in progress, so it no longer looks like nothing happened.
* Changed how settings are saved so that saving is faster and starting the app no longer rewrites them when nothing changed.
* Changed the hourly cleanup of old history so it no longer rewrites your whole history each time.
* Changed installing an update while a window is protected: you can now install it from Settings after confirming, instead of waiting until no window is protected.
* Changed deleting a chat, removing an AI provider and Reset to defaults to ask you first.
* Changed a part of a window that fails to display to show a message in its place, so the rest of the window keeps working; if a whole window fails you can now reload it or copy the details.
* Changed failed actions such as starting a session or protecting a window to show a message instead of doing nothing.

### Fixed

* Fixed the update notice showing as a cut-off strip on the assistant bar that covered its buttons.
* Fixed Check for updates saying you were on the latest version after you had started installing an update.
* Fixed the Install update button in Settings doing nothing after you had chosen Later on the update notice.
* Fixed a failed update download making the update disappear until the next automatic check.
* Fixed an incomplete installation leaving voice transcription silently unavailable; the app now tells you to reinstall.
* Fixed protected windows staying visible to screen sharing for up to half a minute after an internal error.
* Fixed a cancelled sign-out or shutdown un-hiding your protected windows and stopping capture.
* Fixed speech from before you pressed Stop sometimes being sent with your next message.
* Fixed a moment of audio still being sent for transcription after you pressed Stop or withdrew consent.
* Fixed the contents of password and sign-in fields on some pages being read along with the screen text.
* Fixed a screenshot you removed sometimes still being sent; if it cannot be removed you now see a message.
* Fixed audio capture going silent for good after Windows restarted its sound service; it now restarts by itself and tells you.
* Fixed capture not coming back after a disconnected microphone or headset was plugged in again, and Start doing nothing afterwards.
* Fixed the microphone staying on the old device after you chose a new default microphone in Windows.
* Fixed some microphones and sound cards being recorded as silence.
* Fixed transcription dropping to the slower processor-only mode after a brief hiccup.
* Fixed transcripts stopping for the rest of the session after one passage failed to transcribe.
* Fixed instant transcription hanging while connecting, or going quiet without a message when the connection stalled.
* Fixed history and Chat stopping working for the rest of the session after an internal error.
* Fixed a failed save sometimes leaving a question in history without its answer, or an edited Chat message cut short.
* Fixed clearing history while stored data is encrypted leaving search in a broken state.
* Fixed starting a session twice in quick succession leaving minutes counting against a session that could not be ended.
* Fixed stopping sharing and sharing again sometimes ending the new share straight away.
* Fixed sharing hanging on a slow connection, and Leave not working while a helper was still connecting.
* Fixed a failed portable update leaving a mix of old and new files; the previous version is now kept intact.
* Fixed speech recognition processes staying open after the app closed or crashed.
* Fixed Restart as Admin sometimes closing the app without starting it again.
* Fixed pressing Stop briefly freezing the app.
* Fixed a request being charged twice, and its thinking shown twice, when the AI provider failed part way through.
* Fixed screen reading freezing for many seconds when the app in front stopped responding.
* Fixed errors in the Chat window and first-run setup never being shown.
* Fixed first-run setup closing as if your choices were saved when saving them failed.
* Fixed New chat sometimes deleting a chat you had already sent a message in.
* Fixed switching profiles quickly sometimes saving one profile's documents into another.
* Fixed pressing Escape to close a menu or list also closing the assistant panel or stopping the answer.
* Fixed pressing Escape with the panel closed hiding the answer but leaving it running and charging.
* Fixed the onboarding tour taking arrow keys while you typed.
* Fixed double-clicking Retry, Regenerate or Ask again starting two answers.
* Fixed a failed answer sometimes showing "Unknown error" instead of the reason.
* Fixed one slow chart or visual stopping every later one from appearing.
* Fixed deleting a project leaving one of its chats on screen.
* Fixed a model download looking stopped after you switched settings tabs and came back.
* Fixed the Chat setting for how long to keep chats never being saved.
* Fixed the setup screen shown after an update failing to save and appearing again on every start.

## October 26, 2026

**2.1.0**

### New

* Added a Messages section to the main window that lists notices from the seller and license warnings, with a message count on the assistant bar.
* Added opening, closing, zooming and moving a large visual on either screen of a shared session, so both people see the same view.
* Added the host's split view and panel opacity controls to the helper's screen.
* Added opacity buttons and the answer-navigation, redo and split view shortcuts to the desktop helper window.

### Improved

* Changed notices from the seller so they no longer pop up when a session starts.
* Removed the extra notification on the host's screen when a helper sends a message, since the message already shows in the panel.

### Fixed

* Fixed a helper's screen missing the message box, the send button, the screenshot button and the visuals switch.
* Fixed visuals such as architecture pictures showing on the host's screen but not on the helper's.
* Fixed resizing the panel by dragging its edge not resizing it on the helper's screen.
* Fixed scrolling on one side not moving the other side when the helper's window shows the panel smaller.

## October 20, 2026

**2.0.3**

### New

* Added a What's new list under Settings, General, Updates: it shows what the latest update changes before you install it, and what your current version changed.
* Added a clear message in Updates when a check cannot reach the update list, instead of leaving it looking as if you are up to date.

### Fixed

* Fixed Share with a helper stopping at a message that the build has no server address.
* Fixed Check for updates and Install update not working in some builds because they did not know where updates are published.
* Fixed an updated install still reporting an older version number, which could make it offer the same update again.

## September 28, 2026

**2.0.2**

### New

* Added drag and drop of files onto the Chat window, so you can attach documents, photos and text files without opening a file picker.

### Improved

* Changed the Chat sidebar so it can fold down to a slim icon strip, giving your conversation more room.

### Fixed

* Fixed files dropped onto the Chat window not being attached.
