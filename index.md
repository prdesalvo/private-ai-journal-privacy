---
title: Privacy Policy
---

# Privacy Policy for Desandar

_Last updated: November 16, 2026_

Desandar (formerly Private AI Journal) is a local-first journaling app built to keep your writing, recordings, photos, and reflections private. This policy explains how Desandar handles your information.

## Our Privacy Approach

Desandar does not send your journal data to the developer or to a custom backend. The app has:

- No user accounts
- No custom backend
- No analytics SDK
- No advertising SDK
- No third-party trackers
- No third-party AI or transcription service

We do not sell your personal information or use it for advertising.

## Data Stored by Desandar

Desandar stores journal data locally on your device. Depending on the features you use, this can include:

- Journal entries and their titles and dates
- Audio recordings and transcripts
- Photos you choose to attach or include
- Journals, tags, moods, colors, favorites, and saved places
- Entry metadata you choose to include, such as location or weather
- Imported content and export files you create
- Local search, reflection, recap, and other AI-derived data
- Optional Visit History: approximate coordinates, arrival/departure times, and place labels for stops recorded on your iPhone.

## Private iCloud Sync

When iCloud is available, Desandar can sync canonical journal data and attachment payloads through your private iCloud database so they are available on your Apple devices. This may include entries, journals, tags, saved places, audio, and photos.

Your synced content is stored by Apple in your private iCloud account. It is not stored on a Desandar-operated server and is not accessible to the developer. Apple's handling of iCloud data is governed by Apple's terms and privacy policies.

Some derived information—including Reflect conversations, source snapshots, and semantic embeddings—remains local to the device and does not sync through iCloud.

## On-Device Intelligence

Desandar uses Apple on-device intelligence features when they are available. These features can help with transcription cleanup, entry organization, title suggestions, recaps, semantic search, and reflections grounded in your journal.

Desandar does not send journal content to the developer, a custom server, or a third-party AI provider for these features.

## Optional Apple Private Cloud Compute

Desandar processes intelligence features on your device by default. On supported devices and operating systems, you can opt in to Apple's Private Cloud Compute for selected features. These choices are off by default and are saved separately on each device.

- **Reflect and Deeper Recaps:** One shared permission. Reflect sends your question, recent conversation, and permitted retrieved journal passages to Apple's model. In Memories, selecting the cloud model can send permitted entries for the selected period automatically when you open Memories or change periods, as well as when you choose Refresh. Saved results may be reused. Larger periods can be read in sequential parts, with visible progress; a complete result is published only when all required parts finish.
- **Organize and Light Cleanup:** Each has its own permission. When enabled, a requested rewrite sends the selected entry or transcript to Apple's model.
- **Summarize:** Its own permission. When enabled, a requested summary preview sends the selected recording transcript to Apple's model.
- **Custom:** Its own permission. When enabled, a requested draft can send the original entry or transcript, your edit requests, and a complete previous draft when it fits. Follow-up edit requests use Custom's permission independently of the starting preset. Opening the editing sheet or changing its model sends nothing. Editing conversations remain in memory while the sheet is open and are discarded when it closes; they are not saved or synced.

These requests send text, not original audio or photo attachments. A rewrite or summary does not overwrite an entry automatically: you review the draft and choose Apply or Insert. Original recordings and full transcripts are preserved.

Results show where they were generated. Reflect, rewriting, summarizing, and Memories can fall back to on-device processing when Private Cloud Compute is unavailable. A failed Memories refresh preserves an earlier complete saved result when one exists.

The developer does not receive these requests. Read [Apple Intelligence & Privacy](https://www.apple.com/legal/privacy/data/en/intelligence-engine/) for Apple's explanation of how Private Cloud Compute handles requests. You can change the Reflect model in Reflect or manage the feature choices in Settings > Privacy & Sync.

## Optional Device Permissions

Desandar asks for access to device features only when you choose related functionality:

- **Microphone:** Record audio journal entries.
- **Speech Recognition:** Transcribe audio locally when supported.
- **Photo Library and Journaling Suggestions:** Select photos and moments to include.
- **Calendar and Reminders:** Suggest moments for Guided Entry from events or reminders.
- **Health:** Include summaries such as workouts, steps, or sleep in Guided Entry.
- **Location:** Save a place or related weather as private entry metadata. Optional Visit History on iPhone requests Always location access so Apple's low-power visit monitoring can report stops while Desandar is closed. It can miss short stops or report visits late. Apple Maps supplies address and nearby-place lookups, and a visit can be labeled after a nearby business.
- **Face ID, Touch ID, or your device password or passcode:** Lock the app on your device.

These permissions are optional and can be managed in your device's Settings app. Information from an optional source is kept only when you choose to incorporate it into your journal or use the related feature.

## Visit History

Visit History is optional and off until you enable Record Visits. Raw visits stay on the recording iPhone and do not sync to iCloud, Mac, or iPad. Choose a retention period of 7, 30, or 90 days; older visits are removed when Desandar next runs, and shortening the period removes older visits immediately. You can stop recording and delete all raw visits without deleting entries already saved. Changing iCloud accounts clears the device's raw visit history.

Raw visit history is not included in Reflect or search. You choose visits before using them in on-device Guided Entry. Details you save into an entry become journal content and follow that entry's sync and AI permissions. The same applies to Calendar, Reminders, Health, location, and weather details you choose to save into entries.

## Apple System Features

If you enable features such as Spotlight, Siri, Shortcuts, widgets, or App Intents, limited journal metadata or an app action may be made available to that Apple system feature. Desandar uses conservative metadata and authentication gates to avoid exposing full private journal text by default.

## Imports, Exports, and Sharing

Imports happen after you choose a file, share text or audio into Desandar, or explicitly hand off content from another app or a Shortcut. Shared content is staged locally for import or review. If you export or share from Desandar, the app creates files on your device in formats such as Markdown, JSON, or ZIP and sends them only to the destination you select. Nothing is uploaded automatically to a Desandar server.

## Retention and Deletion

Journal data remains on your device, and synced journal data remains in your private iCloud account, until you delete it. You can delete entries and derived AI memory from within Desandar. Deletions of synced journal data propagate through iCloud when sync is available.

Uninstalling Desandar removes its local app data but may not remove data retained in your private iCloud account. You can manage iCloud storage through your Apple Account settings.

Delete AI Memory removes local semantic embeddings, entry digests, saved recaps, and Reflect source snapshots. Original entries, attachments, tags, and Reflect conversations are kept. Cloud Usage diagnostics contain feature names, times, outcomes, and coarse Apple status, not journal text, prompts, responses, or raw error messages. The latest 50 attempts and daily attempt counts stay in device-local preferences; they are shared only if you explicitly choose the system share action.

## Changes to This Policy

If this policy changes, the “Last updated” date at the top of this page will be updated.

## Contact

For privacy questions or support, email [talus.llano-3k@icloud.com](mailto:talus.llano-3k@icloud.com) or visit the [Desandar support page](./support/).
