# soundBlade 3.0 — Release Notes

**soundBlade 3.0 Beta. An NDA must be signed to use this software.**

Every release, newest first. Each links to its full notes below.

<a name="versions"></a>
## Versions

- **[1.1.109](#v1-1-109)** — 2026-10-09
  - ADMs with objects play in 7.1.4 — this changes the sound
  - Render (Preview)
  - Exports keep heights silent
  - Faster renders of MP4, FLAC and Auro
- **[1.1.108](#v1-1-108)** — 2026-10-09
  - Binaural now plays the master as authored
  - Auro-Matic Upmix (Preview, monitoring only)
  - Save deliverables from the Preview
  - Preview meters
- **[1.1.107](#v1-1-107)** — 2026-10-07
  - Auro-3D: named as Auro names them
  - Artist Connection
- **[1.1.106](#v1-1-106)** — 2026-10-06
  - Objects: room-centric (changes what plays and prints)
  - Auro-3D and Auro-Cx
  - Preview
  - EDL
- **[1.1.105](#v1-1-105)** — 2026-10-04
  - Artist Connection: albums and sharing for review
  - Claude can control soundBlade (off by default)
  - AC Connect (off by default, on your network)
- **[1.1.104](#v1-1-104)** — 2026-10-04
  - Removing the last file asks whether to delete the album info too
  - Hover a file to see its whole name
  - Hover the room
- **[1.1.103](#v1-1-103)** — 2026-10-03
  - Preview window — checking a stereo album
  - Metadata
  - DDEX
  - Loudness
- **[1.1.102](#v1-1-102)** — 2026-09-27
  - Speaker layouts
  - Preview window
  - Waveform caches
- **[1.1.101](#v1-1-101)** — 2026-09-26
  - A clip fade you hear is now bit-for-bit the fade that exports
  - One small change you may notice
  - Null test a fade
  - Play a busy EDL at a 512 buffer
- **[1.1.100](#v1-1-100)** — 2026-09-26
  - This release answers the latest round of tester reports.
- **[1.1.99](#v1-1-99)** — 2026-09-26
  - Fixed: playback could hear a plug-in out of time against the other tracks
  - Fixed: changing a plug-in while playing could slide the mix
- **[1.1.98](#v1-1-98)** — 2026-09-26
  - Please update from 1.1.97. It fixes an export problem in 1.1.97.
- **[1.1.97](#v1-1-97)** — 2026-09-25
  - Streaming export is now the default.
- **[1.1.96](#v1-1-96)** — 2026-09-25
  - A new way to export — a second at a time, straight to disk — ready to try, and a fix for plug-ins on very short Desk Events.
- **[1.1.95](#v1-1-95)** — 2026-09-25
  - Plug-ins in Edit Groups, plug-in latency, and playback that no longer drops out when the disk falls behind.
- **[1.1.94](#v1-1-94)** — 2026-09-24
  - One change to the Export window.
- **[1.1.93](#v1-1-93)** — 2026-09-24
  - Export fixes and a better question at the end of every export.
- **[1.1.92](#v1-1-92)** — 2026-09-24
  - Two things testers asked for.
- **[1.1.91](#v1-1-91)** — 2026-09-24
  - DDEX arrives in the Preview, plus layout and header fixes.
- **[1.1.90](#v1-1-90)** — 2026-09-23
  - A small follow-up to 1.1.89.
- **[1.1.89](#v1-1-89)** — 2026-09-23
  - Metadata you can gather, import and deliver: a metadata record beside every file, import from CSV or Excel into Mark Info and the Preview, a cover image for the album, and exported songs that carry it all with them. Plus a compact EDL header for locked EDLs.
- **[1.1.88](#v1-1-88)** — 2026-09-22
  - Speaker naming in SMPTE or ITU-R, a Room view seen from the listener's seat, diffuse objects heard as diffuse, and ADM object timing read correctly. This release also carries the playback corrections prepared as 1.1.87, which was withdrawn before most testers received it.
- **[1.1.87](#v1-1-87)** — 2026-09-21
  - Audio correctness: nothing left over when you press Play, Desk Events that start and end on the sample you put them on, and an object panner that moves smoothly and prints what you monitored.
- **[1.1.86](#v1-1-86)** — 2026-09-21
  - Auro-Cx: soundBlade now decodes Auro's coded bitstream, not only the carrier.
- **[1.1.85](#v1-1-85)** — 2026-09-20
  - Small corrections to 1.1.84's MP4 support, found by testing it against a real set of video files.
- **[1.1.84](#v1-1-84)** — 2026-09-20
  - Audio out of video files. An MP4 opens like any other master — including one with an Auro-3D carrier inside it — and brings its picture with it.
- **[1.1.83](#v1-1-83)** — 2026-09-20
  - Recording, the Preview window, and the two Edit Fade Mode items from 1.1.82 that were not actually fixed.
- **[1.1.82](#v1-1-82)** — 2026-09-20
  - Five fixes from tester reports: recording, Edit Fade Mode, and what the playhead does when you stop.
- **[1.1.81](#v1-1-81)** — 2026-09-20
  - Audio correctness. Several faults in muting, the master strip and binaural monitoring that have been there a long time, found by using the Preview window hard for a day. Everything here is in the audio path, so it is worth a listen rather than a glance.
- **[1.1.80](#v1-1-80)** — 2026-09-16
  - One Export window for sound files, ADM and DDP; timecode fields you can type into; and a recording fix — the track's input list was empty until you armed a track.
- **[1.1.79](#v1-1-79)** — 2026-09-15
  - A built-in Test Suite, playback that follows the Source Layout, exact plug-in latency compensation, and a warning light when playback falls behind.
- **[1.1.78](#v1-1-78)** — 2026-09-14
  - ADM masters carry their title, album and ISRC in and out, ADMs can cross-fade on an album, and filename tags are now one list for the whole app.
- **[1.1.77](#v1-1-77)** — 2026-09-14
  - Assemble Album builds one EDL and renders only what you tick, the Preview shows each channel's peak and an overview, and the Object View turns in 3D.
- **[1.1.76](#v1-1-76)** — 2026-09-13
  - PQ List now makes a proper album log sheet as a PDF, and Mark Info holds the album's Title and Artist instead of DDP controls.
- **[1.1.75](#v1-1-75)** — 2026-09-13
  - Titles and album go into ADM masters, metadata comes in from a CSV, PCM masters open as separate tracks, and the video commands move to where you would look for them.
- **[1.1.74](#v1-1-74)** — 2026-09-13
  - Choose which tracks you want to see — in the Preview before a master is opened, and in an EDL's Layout — and a fix for a crash on quit.
- **[1.1.73](#v1-1-73)** — 2026-09-13
  - Albums ask how programmes meet and cross-fade for real, Projects remember their windows, the Object View reads better, and the Desk explains itself.
- **[1.1.72](#v1-1-72)** — 2026-09-12
  - Edit Fade Mode's Prev and Next now step through every edit on the track.
- **[1.1.71](#v1-1-71)** — 2026-09-12
  - Edit Fade Mode brought in line with the soundBlade manual (4.2): selections, Lock Sound, Ripple Until Black, Align Fades and Audition Both now behave as documented, and an edit in EFM carries across every track in the Edit Group.
- **[1.1.70](#v1-1-70)** — 2026-09-12
  - Edit Fade Mode plays one half of a crossfade, opens both fades across a gap, and keeps the fade in place while you zoom. Export gains Genre and tells you when an ISRC was left out.
- **[1.1.69](#v1-1-69)** — 2026-09-12
  - A new metadata window for files, marks that keep their order and follow Red Book spacing, a rearranged EDL header, and an About box.
- **[1.1.68](#v1-1-68)** — 2026-09-12
  - Edit Fade Mode gets its menu back, the Fade Library gets its Defaults, and four things that quietly did nothing now do something.
- **[1.1.67](#v1-1-67)** — 2026-09-12
  - A tighter EDL header, Stop that returns to where you started, and the Edit Target spelled out on every track.
- **[1.1.66](#v1-1-66)** — 2026-09-10
  - Edit Lock — cut a programme across all of its deliverables at once — plus a run of editing and interface fixes.
- **[1.1.65](#v1-1-65)** — 2026-09-10
  - No more privacy prompts at launch, long jobs run in the background, and the Preview window grows up: picture, measured loudness, and the album's own render settings.
- **[1.1.64](#v1-1-64)** — 2026-09-10
  - The Preview window becomes a window of its own — it no longer belongs to a Project — plus a crash fix on the audio thread and a run of Preview corrections.
- **[1.1.63](#v1-1-63)** — 2026-09-10
  - A new Preview ADM window, and fixes for ADM import on top of 1.1.62's recording.
- **[1.1.62](#v1-1-62)** — 2026-09-09
  - Recording. soundBlade can now record into the EDL.
- **[1.1.61](#v1-1-61)** — 2026-09-07
  - A Custom source layout, for material whose channel order matches no standard layout.
- **[1.1.60](#v1-1-60)** — 2026-09-07
  - Fixes export name tags not being remembered, makes them per project, and teaches the Auto source layout to read speaker names off dropped filenames.
- **[1.1.59](#v1-1-59)** — 2026-09-07
  - Export window tidying, layout names in filenames, and Analog Black to Marks working from a clip selection.
- **[1.1.58](#v1-1-58)** — 2026-09-07
  - Every exported file now names itself from its own facts.
- **[1.1.57](#v1-1-57)** — 2026-09-07
  - Build export filenames from draggable tags, ADM export gives every object the same end time, and Sync To Matching moves the Destination. (1.1.56 was built but never published — a release-script failure. Everything intended for it is here.)
- **[1.1.55](#v1-1-55)** — 2026-09-07
  - Sync To Matching — line up EDLs against a reference by measuring the audio rather than trusting nominal positions. Plus a round of Album Mode fixes from testing 1.1.54, and the read speed-up that 1.1.54 announced but did not actually deliver.
- **[1.1.54](#v1-1-54)** — 2026-09-07
  - Album Mode: import several ADMs at once and assemble them into one album, each programme rendered to the speaker layout you choose and every ADM kept open to drill into. Plus a large speed-up to reading wide multi-channel files.
- **[1.1.53](#v1-1-53)** — 2026-09-07
  - Export Tracks comes to the Export Sound File window: split a master at its marks into one file per track, carrying each track's own title and ISRC. Change Plug-in now actually changes the plug-in, and the export window no longer blocks the EDL while it is open.
- **[1.1.52](#v1-1-52)** — 2026-09-05
  - The Files/Marks/Layout panel becomes its own window, the soundBlade menu works with no Project open, and a Master Bus plug-in narrower than the bus now covers all of it.
- **[1.1.51](#v1-1-51)** — 2026-09-04
  - Fixes for dropping multiple files, the Desk window, Project Settings, and ADM import's Speaker Layout.
- **[1.1.50](#v1-1-50)** — 2026-09-03
  - A plug-in processing bug traced all the way from Export to the Master Bus, a much faster ADM import/reopen, and a handful of Desk window fixes.
- **[1.1.49](#v1-1-49)** — 2026-08-30
  - Dragging segments now has one clear set of rules, plus fixes to clip gain, the lane's context menu, and the Delete key.
- **[1.1.48](#v1-1-48)** — 2026-08-28
  - Resequencing by dragging segments now works as the manual describes it, plus scroll-wheel and header changes.
- **[1.1.47](#v1-1-47)** — 2026-08-28
  - A follow-up to 1.1.46's sample-rate work: one readout instead of two, a rate that says what it means, and a crash on closing a project.
- **[1.1.46](#v1-1-46)** — 2026-08-28
  - Everything since 1.1.42. Releases 1.1.43, 1.1.44 and 1.1.45 went out with 1.1.42's notes inside the DMG by mistake, so this file covers all four.
- **[1.1.42](#v1-1-42)** — 2026-08-26
  - Two correctness fixes.
- **[1.1.41](#v1-1-41)** — 2026-08-26
  - Tester-reported fixes.
- **[1.1.40](#v1-1-40)** — 2026-08-25
  - New: Export Sound File…
  - Sonic HD SRC replaces the previous sample-rate conversion
  - Fixed: dropouts around plug-ins that report latency
  - Artist Connection: Albums and Projects
- **[1.1.34](#v1-1-34)** — 2026-08-23
  - New: Manual Per-Track Panning
  - Binaural HRTF Presets
  - Also in this release
- **[1.1.33](#v1-1-33)** — 2026-08-23
  - New: Binaural HRTF Monitoring
  - New: Realtime Plugin Delay Compensation
  - Artist Connection
  - Also in this release
- **[1.1.32](#v1-1-32)** — 2026-08-22
  - The Track Header
  - Segment Gain
  - Waveforms
  - Edit Fade Mode
- **[1.1.31](#v1-1-31)** — 2026-08-22
  - The Desk
  - Editing
  - Project & window
  - Also in this release
- **[1.1.30](#v1-1-30)** — 2026-08-17
  - Edit Fade Mode
  - DDP
  - Also in this release
- **[1.1.29](#v1-1-29)** — 2026-08-12
  - The two layout buttons, explained where you need it
  - Also in this release
- **[1.1.28](#v1-1-28)** — 2026-08-11
  - Loudness measurement follows the content, not the machine
  - Also in this release
- **[1.1.27](#v1-1-27)** — 2026-08-11
  - Film & TV loudness
  - Also in this release
- **[1.1.26](#v1-1-26)** — 2026-08-11
  - Artist Connection
  - Also in this release
  - Known limitations
  - 1.1.24
- **[1.1.24](#v1-1-24)** — 2026-08-09
  - Please update from 1.1.23
  - The start/stop click is back, for now
- **[1.1.23](#v1-1-23)** — 2026-08-09
  - No more click on start and stop
  - Please check this one and report back
- **[1.1.22](#v1-1-22)** — 2026-08-09
  - Playback no longer needs a trip to Audio I/O first
  - The window no longer locks up while playing
  - Objects are visible in the Object View
  - soundBlade no longer asks about sample rate
- **[1.1.21](#v1-1-21)** — 2026-08-08
  - Dialog buttons did the wrong thing
  - The EDL's sample rate is now visible
  - Track View
  - Other changes
- **[1.1.20](#v1-1-20)** — 2026-08-07
  - Opening a large ADM
  - Playback no longer reads the disk on the audio thread
  - Clip gain
  - Export now prints polarity
- **[1.1.19](#v1-1-19)** — 2026-08-07
  - Clicks on start and stop are gone
  - Clips are selected by their title bar
  - Text View
  - Known limitations
- **[1.1.18](#v1-1-18)** — 2026-08-07
  - Exports now carry your processing
  - Dither
  - The EDL Desk
  - Other changes
- **[1.1.17](#v1-1-17)** — 2026-08-05
  - Large sessions open far faster
  - Track Display Type
  - ADM import
  - Working with several tracks at once
- **[1.1.16](#v1-1-16)** — 2026-08-04
  - CD-Text now reaches the disc
  - The Mark menu generates marks from the edit
  - Plugin automation
  - The EDL Desk

---

<a name="v1-1-109"></a>
## 1.1.109 — 2026-10-09

### ADMs with objects play in 7.1.4 — this changes the sound

- **An ADM whose bed has fewer than four height speakers now plays in 7.1.4**
  (in the Preview, an EDL opened from it, Assemble Album and every export of
  it). Until now its objects were squeezed into the bed's own speakers — a
  7.1.2 bed put every object's height into two top-middle speakers, which were
  then spread over a 7.1.4's four heights. Objects now go straight to the four
  heights, as a Dolby or EBU render places them.
- **Bed channels go to the speaker their label names.** One 7.1.4 does not have
  (a 7.1.2's top middles) is placed at its own position.
- **Dolby's bed labels ("RC_Ltf") are recognised as heights** — a Dolby 5.1.2
  bed was taken for 7.1 — and **a 5.1.4 bed is no longer taken for 7.1.2**.
- ADM EDLs saved earlier keep their layout; open the ADM again for the new one.

### Render (Preview)

- **Render...** replaces the Save buttons beside Binaural and Monitor: the
  selected files' deliverables — **Binaural** and/or **7.1.4** — one file at a
  time in the background, 24-bit WAV beside each master (or in the download
  folder), with its metadata, added to the list. Nothing is ticked until you
  tick it.
- **Each file shows its progress** as a small bar at the end of its row.
- **A master narrower than 7.1.4 is named before it renders** — its 7.1.4
  carries the original channels only, and its heights are silent.
- Stereo masters and streams are skipped, with the reason.

### Exports keep heights silent

- **Every layout export — Export Sound File, Album Renders, Render — keeps a
  narrower master's height speakers silent.** A 5.1 master exported to 7.1.4
  used to reach the top rears about 13 dB down. A downmix still folds heights in.

### Faster renders of MP4, FLAC and Auro

- A render, export or Measure of a decoded file (MP4, FLAC, Auro) reads each
  stretch once for all its channels — a 12-channel MP4 with video crawled.

### What each file becomes

What the Preview — and a file opened as an EDL — does with each kind of
master, on each output. "Plays in" is the layout the Desk shows and every
render starts from; it is set when the file is opened and does not change when
you switch monitors.

| Your file | Plays in | On speakers | On headphones (Binaural) | Render 7.1.4 | Render Binaural |
|---|---|---|---|---|---|
| Stereo | Stereo | folded to your speakers | not binauralized | skipped | skipped |
| 5.1 / 7.1 | its own layout | folded to your speakers | the renderer chosen in Settings | the original channels, **heights silent** (you are warned first) | the renderer chosen in Settings |
| 5.1.4, 7.1.4, 9.1.6 … | its own layout | folded | Settings renderer | 7.1.4 as is; wider is folded, heights into heights | Settings renderer |
| ADM, bed only | its bed | folded | Settings renderer | as its bed's layout | Settings renderer |
| **ADM with objects** (bed with fewer than four heights, or no bed) | **7.1.4** — objects placed straight into it | folded from 7.1.4 | Settings renderer | as is | Settings renderer |
| ADM with objects, bed with four or more heights | its bed | folded | Settings renderer | folded, heights into heights | Settings renderer |
| Auro-3D carrier | its Auro layout | a smaller system gets Auro's own decode; otherwise straight through | **Auro's renderer, always** | its own layout into 7.1.4 | Auro's renderer |
| Auro-Cx | its bed | folded | Settings renderer | as a channel file | Settings renderer |

- **Folded** means each speaker of the file goes to where it belongs among your
  speakers; nothing is added.
- **Every layout render — Render, Export, Album Renders — keeps heights where
  they are**: a speaker the file has goes straight across, any other only among
  speakers at its own height, so a narrower master's heights stay silent. A
  downmix (to Stereo or 5.1) still folds the heights in.
- **Binaural plays the master as authored.** The Settings renderer is Auro
  (the default), SOFA with your HRTF, or Apple Spatial Audio.
- **Auro-Matic Upmix** (Monitor menu, off by default) upmixes on speakers and
  headphones where Auro supports both layouts — never in a render or export.
- **A Render carries no Solo, Mute, DIM, Main volume or upmix**, and in a batch
  no Desk faders: each file is rendered as authored.


### For testers

- Open an ADM with a 7.1.2 bed and objects: it should read 7.1.4, with objects
  in all four heights.
- Render a 5.1 and an ADM to 7.1.4 and Binaural; play each against the Preview.

Everything else is as in 1.1.108.

[Back to the list of versions](#versions)

---

<a name="v1-1-108"></a>
## 1.1.108 — 2026-10-09

### Binaural now plays the master as authored

- **The Auro binaural renderer no longer upmixes.** Until now it ran in a mode
  that upmixes everything (Auro-Matic for Headphones), so a 5.1 or 7.1.4 master
  on headphones was heard upmixed, not as authored. It now plays the material
  as it is. **Binaural through Auro will sound different — drier, with no
  added height.**

### Auro-Matic Upmix (Preview, monitoring only)

- **Monitor menu > Auro-Matic Upmix** — off by default, remembered. On
  speakers, Auro's engine upmixes the material to the Monitor layout in place
  of soundBlade's own fold; on headphones, Auro's binaural upmixes again.
- Offered only where Auro renders both layouts: 5.1, 7.1, 5.1.4, 7.1.4 and the
  Auro configurations (not 9.1.6, 7.1.6, 7.1.2 or 5.1.2). The Monitor read-out
  says "→ Auro-Matic" while it is on.
- **Never in an export, Measure or a Save** — it is a listening choice.

### Save deliverables from the Preview

- **Binaural Save** — a **Save** button beside Binaural while it is on: the
  selected master rendered through the binaural renderer chosen in Settings
  (Auro's for Auro material) to a 2-channel, 24-bit WAV, "<name> - Binaural".
- **Monitor Save** — a **Save** button beside the Monitor button when it is
  7.1.4 or 5.1: what you are monitoring, rendered by soundBlade's own renderer
  (an ADM's objects placed in the room) to "<name> - 7.1.4" or
  "<name> - Surround", 24-bit.
- Both: the full decode with the Desk faders and polarity (Solo, Mute, DIM and
  the upmix are not in it), saved beside the master — or in the download folder
  for an Artist Connection download — with the master's metadata (Layout set to
  what the file is), and added to the list.
- **A Save runs in the background** — pick other files and play them while it
  works; the button shows its progress and cancels it. (Measure renders its own
  copy too.)

### Preview meters

- **Solo and Mute under every Desk meter.** A channel silenced by Solo or Mute
  draws no meter; loudness and Measure are unaffected.
- **The Monitor meters have a level readout and Solo/Mute** like the Desk's —
  Solo/Mute there act on the speaker itself, monitoring only — and follow the
  Desk's **P/H** peak hold (Ctrl-click clears both rows). Channel names are the
  Desk's size.
- "(pinned)" is gone from the Monitor button.

### Artist Connection

- **Settings > Accounts has one Login / Logout button** that follows the
  sign-in live, and a **Reveal Log** button.
- **The Files window's Artist Connection tab and the Preview's cloud button
  appear only while signed in.**
- **Downloads go to a folder you choose** — asked at the first download,
  remembered, shown at the bottom of the cloud view with **Set Folder...**.
- **Downloads keep their extension.** Some library items carry none; the file
  type is now taken from the download itself (or the file's own bytes), and a
  file is never saved without one.
- **Right-click a downloaded file > Delete Downloaded File...** removes this
  computer's copy (it stays in Artist Connection).
- **Double-click a picture in the Library** to make it the album cover (asks
  first, and asks before replacing a cover).
- AC Connect names itself after the app, and moves to the next free port when
  its usual one is taken.

### Also

- **Application Settings is in the soundBlade menu only**, beside Audio I/O
  Settings (removed from the File menu).
- **Preview file list: right-click > Show File Location...**
- **Clicking a file that has video opens the video window** if it is closed.
- **Drop a picture anywhere on the Preview** to make it the album cover.
- Settings windows' small text is easier to read.
- Fixed: a leak reported on quit after viewing album covers.

### For testers

- Binaural on a 5.1 or 7.1.4 master with the Auro renderer: still binaural, and
  no added height? Then tick Auro-Matic Upmix and compare.
- A 5.1 master on 7.1.4 with Auro-Matic Upmix on: every channel on the right
  speaker, heights alive.
- Save a binaural and a 7.1.4 version of an ADM; play each against the Preview.
- Download from Artist Connection into a chosen folder; check the extensions.

Everything else is as in 1.1.107.

[Back to the list of versions](#versions)

---

<a name="v1-1-107"></a>
## 1.1.107 — 2026-10-07

### Auro-3D: named as Auro names them

- **An Auro file (a carrier or Auro-Cx) is named by the configuration it
  declares**, as listed in Auro's own licensee manual — for example
  "Auro 11.1 (7.1+4H)", "Auro 9.1 (5.1+4H)", "Auro 13.1 (7.1+5H+T)" — and its
  channels take Auro's own names in Auro's own order: L R C LFE Ls Rs Cs Lb Rb
  HL HR HC T HLs HRs.
- **Every Auro configuration is recognised**: LCR, LCRS, Quad, 5.0/5.1/7.0/7.1
  Surround, Auro-222, Auro 8.0, 9.0, 9.1, 10.0, 10.1, both 11.0s, both 11.1s,
  Auro 12.1, 13.0 and 13.1. 5.1.2 and 7.1.2 keep our names.
- **A 7.1.4 Auro master now reads "Auro 11.1 (7.1+4H)"** with HL/HR/HLs/HRs
  rows, where it read "7.1.4" with Ltf/Rtf/Ltr/Rtr. **It sounds the same**:
  monitored or routed onto our layout of the same speakers (7.1.4, 5.1.4, 7.1,
  5.1), an Auro file goes straight through, channel for channel — HL to Ltf,
  HLs to Ltr, and so on — never re-panned.
- **Auro configurations appear in menus only for Auro material** — the
  Preview's Monitor menu and Speaker Layout dialog when the selected file is
  Auro, an EDL's Source menu and layout dialogs when it holds an Auro clip. They
  are no longer offered in Export or Album Renders.

### Artist Connection

- **Projects lists the studio's whole project list**, wherever each was made
  (the portal, another Mac, here) — it used to show only projects made in this
  copy of soundBlade. Newest first, with Reload. A published project's
  **Get Links** shows its share links.
- **Albums is a tab of the panel**, beside Library and Projects — no separate
  window. The Library's "Albums..." goes there too. (The Albums tab used to say
  "Album browsing isn't enabled for this integration".)
- **Album covers** show as thumbnails in the albums list, in taller rows.
- **The Preview's cloud view has the same Library | Albums | Projects tabs**
  (read-only there: albums list and open in the portal; no Set Cover or Share).
- **Preview: the Open (folder) button returns from the cloud view** to the file
  list as you left it; from the list it opens the file chooser as before.

### For testers

- Open an Auro 7.1.4 master in the Preview and an EDL: rows should read
  HL HR HLs HRs and it should sound exactly as in 1.1.106.
- Artist Connection > Projects: projects made in the portal should be listed.
- Albums: covers should appear in the list.

Everything else is as in 1.1.106.

[Back to the list of versions](#versions)

---

<a name="v1-1-106"></a>
## 1.1.106 — 2026-10-06

### Objects: room-centric (changes what plays and prints)

- **Speakers stand in the room's corners**, as engineers lay out a room
  (ITU-R BS.2127): L/R in the front corners, surrounds and rears in the rear
  corners, tops in the ceiling corners. Polar (EBU) object positions are
  converted into the room the same way.
- **The object panner follows the same rule**, so an object is heard where it
  is drawn. **This changes the sound of Dolby-style (Cartesian) objects near
  the corners** — in playback, exports and Measure alike.
- **Room-centric** tick in the object view switches back to the old
  listener-centred sphere, sound and picture together, for comparison.
- **Isometric** tick: the Room view drawn without perspective, as macOS
  Audio MIDI Setup draws a room. A lounge chair marks the listening position.
- Soloing an object shows the others as muted (visible, dimmed, no level).

### Auro-3D and Auro-Cx

- **Auro speaker configurations**: Auro 9.1, 10.1, 11.1, 12.1 and 13.1 —
  offered for monitoring, and used to name any file that declares one (Auro
  9.1 used to read as 5.1.4 or 7.1.2).
- **Auro-Cx in the Preview**: the Auro badge, "Auro-Cx" with its declared
  quality, speaker names, declared loudness, and its tags and cover.
- **Auro-Cx inside a movie MP4 now decodes** (it showed as an undecoded
  "A3DS lossy" track).
- Auro carrier detection is lighter on ordinary files.
- Dropping a file that declares its speakers (Auro-Cx, Auro, MP4 or WAV/FLAC
  channel mask) onto an EDL names each track after its speaker and routes it
  there.

### Preview

- **Reorder the file list**: drag rows, the row menu (Move Up/Down/to
  Top/Bottom), or Cmd-Option-Up/Down. After a metadata sheet import, it offers
  to put the list in the sheet's track order.
- **Cmd-A** selects every file.
- **Monitor menu**: Follow File (the default) or pin a layout for every file;
  only layouts your output device can carry; "Channel Based" removed.
- **Stereo**: the Source read-out says Stereo (or Binaural); no Monitor
  control or headphones button when it is stereo in and stereo out.
- **Source** is a read-out of what the file declares, not a menu.
- The ADM column shows only for ADMs; DIM lights when engaged.
- **Export DDEX** clears waveform cache folders from the delivery first.

### EDL

- **File > Open File...** takes several files at once.

### For testers

- Open an ADM with objects and toggle **Room-centric** while it plays.
- Open an Auro-Cx movie (or a .mp4a) in the Preview.
- Drag a few rows of the Preview's list into a new order.

Everything else is as in 1.1.105.

[Back to the list of versions](#versions)

---

<a name="v1-1-105"></a>
## 1.1.105 — 2026-10-04

### Artist Connection: albums and sharing for review

- **Create Album** from a folder or a selection: tracks in Track Number
  order, titled from each file's Title tag. Nothing is pre-selected.
- **Albums window**: reorder and rename tracks, set a cover (a library image,
  or one from disk), **Share** for review and **End Review**. Sharing makes a
  `<album> (Review)` project and gives you its link and a QR code; sharing
  again gives the same link. **Review links are public.**
- **Uploads**: one upload queue for the whole app, so closing a Project
  window no longer stops an upload; quitting asks first. Subfolders are
  mirrored.
- Fixed: every upload was refused by storage (403).
- Fixed: a studio's top level was listed twice.

### Claude can control soundBlade (off by default)

- Application Settings > Accounts > Claude: tick **Let Claude control
  soundBlade** to let a Claude Code or Claude Desktop session browse your
  Artist Connection library, upload, make albums and share them.
  **Copy Claude Code Command** and **Add to Claude Desktop** set it up.
  It listens on this Mac only (127.0.0.1) and needs a private token.

### AC Connect (off by default, on your network)

- Application Settings > Accounts: let the Artist Connection app play a
  playlist into soundBlade's Preview. **Anyone on your network can then send
  it something to play** — the protocol has no login. macOS will ask for
  Local Network access; if you refuse, the status line says where to allow it.
- Not yet tested from a phone.

### Fixes

- Quitting with Application Settings (or another dialog) open no longer
  trips an error on the way out.
- DDEX: if a delivery's folder cannot be read, it says so, rather than
  reporting MD5 mismatches.

### For testers

- Make an album from a folder of tagged files and check the track order and
  titles; share it and open the link.
- Quit with Application Settings open.

Everything else is as in 1.1.104.

[Back to the list of versions](#versions)

---

<a name="v1-1-104"></a>
## 1.1.104 — 2026-10-04

### Preview window

- **Removing the last file asks whether to delete the album info too** — its
  title, artist, UPC, description and cover are kept with the list, and would
  otherwise carry into the next album.
- **Hover a file to see its whole name**, when it is cut off in the list.
- **Hover the room** (object view) for how to move it: drag to rotate,
  double-click to reset, scroll to zoom.

### For testers

- Remove every file from the Preview's list with Album Info set — you should
  be asked whether to delete it.

Everything else is as in 1.1.103.

[Back to the list of versions](#versions)

---

<a name="v1-1-103"></a>
## 1.1.103 — 2026-10-03

### Preview window — checking a stereo album

- **Lists.** Save List saves the list (with its Featured and Skip ticks) as a
  `.previewlist`; Open asks whether to replace the list or add to it, and opens
  a saved list or an EDL (one entry, a row per track — an EDL with edits is
  refused). Remove from List removes every selected row, without a question.
  Drop a folder to add the audio files in it (not its sub-folders).
- **Stereo files get a simpler window:** no F/Skip columns, no Source button,
  and Binaural is a choice in the Monitor menu (which stops at Stereo) instead
  of its own button. The object view folds away, and the Monitor meters hide
  when they would only repeat the Desk.
- **The bar between the read-outs and the Desk can be dragged** to move the
  loudness figures right. Double-click it to reset.
- **The main volume fader shows what is going out** — the loudest output
  channel, after the fader — with a peak line and an over mark.
- **The SR lamp above it lights green when the file is sample-rate converted**
  to the device's rate, and is the same lamp as the Desk's.
- **Audio I/O in the Preview now sets the Preview's own device.** It used to
  open the Project window's settings, so the Preview could go on playing to a
  device nobody chose (heard as silence with the meters moving).
- Album Info is a button beside Export; the left button row is a size smaller;
  every button there, and the loudness block, has a tooltip.

### Metadata

- **Drop a CSV, TXT, TSV or Excel sheet on the Preview to import it.** Rows are
  matched to files by ISRC, by **name** (so a list sorted by name still finds
  its rows — "Enough Aint Enough_AHP.flac" finds "Enough Ain't Enough"), or by
  track number. The review now has **Import All** and **Import ISRC Only**.
- **Album fields come in from the sheet** where a column repeats the album on
  every row (Album Title, Artist Name On Cover Art, Album UPC, Release Date,
  C-Line...). A column whose rows disagree is left with the tracks.
- **Album Info** (button, or right-click the cover) edits the album by hand:
  title, artist, label, genre, release date, UPC, catalog number, copyright,
  parental advisory, **description**, and the album's **delivery layout**
  (e.g. Binaural). Also in Mark Info.
- **Drop an image on the cover square** to use it.

### DDEX

- **Dropping a DDEX message replaces the list** (after asking) with its whole
  release — files, each file's metadata, the album and its cover.
- **Export never asks for a layout.** A file's own, else what the file
  declares, else the album's layout, else two channels are Stereo. Edit
  Metadata shows in grey what an unset layout will export as.
- The album description is written as the release's Synopsis. No end date is
  written into a first delivery.
- Fixed a crash pressing Import in the DDEX report.

### Loudness

- **Measure saves its figures with the file** (in the metadata record beside
  it) and shows them whenever the file is selected, until the file changes.
- Save to File writes them into a WAV's existing bext loudness fields, leaving
  the rest of the chunk untouched.
- A bext field marked "not measured" now shows "--" (it read as 327.7).

### EDLs

- **Assemble Album takes stereo (and any PCM) files**, one track per channel,
  in order and meeting as you choose — no "doesn't contain ADM" alert.
- **Edit Fade Mode opens from a time selection around an edit**, a butt splice
  included.
- An EDL opened from the Preview takes its sample rate from the first file and
  locks it, on every route.

### Artist Connection

- **Every format streams** — WAV, FLAC, MP4, Auro-Cx and ADM. Download is
  offered, never required. The Files window keeps its Artist Connection tab,
  and the Preview has a read-only cloud tab for checking streamed masters.

### Fixes

- **Auro binaural was silent** — fixed.
- Channel Based monitoring passes the channels straight through.

### For testers

- **Stereo album:** drop a folder of stereo masters and its spreadsheet on the
  Preview, check every row matches, Import All, then Export > DDEX.
- **Loudness:** Measure a file, select another, come back — the figures should
  read "measured" with the date.
- **Assemble Album** with stereo files, butt splice, then select across a
  splice and press Cmd-F.

Everything else is as in 1.1.102.

[Back to the list of versions](#versions)

---

<a name="v1-1-102"></a>
## 1.1.102 — 2026-09-27

### Speaker layouts

- **"Custom" is shown wherever it applies.** When a layout's speaker-to-output
  map is hand-built, the EDL's Monitor button, the Desk's Monitor row and the
  Preview's Monitor button now read **Custom** instead of the layout's name
  (the tooltip says which layout it is built on). The Speaker Layout dialog
  follows the same rule, and its Order box now shows SMPTE or Film to match
  a map in either standard order, so the button and the dialog always agree.
- **The Preview's Monitor menu has a Custom item**, bringing back your
  hand-built map. Picking a plain layout there now means that layout's
  standard order; a hand-built map is kept as Custom rather than lost.

### Preview window

- **Binaural on an Auro-3D file keeps all its channels.** With Binaural on, an
  Auro master still shows its decoded rows (12 for 7.1.4) and only the monitor
  becomes the headphone pair — rendered by Auro's own binaural renderer. It
  used to collapse the rows to L and R and leave the monitor meters showing
  the speaker layout.
- **Drag bar between the file list and the Layout list.** Drag it to resize
  the file list; double-click it to reset. The Overview (waveform) column is
  the one that grows or shrinks — the other columns keep their width.
- **Measure fills the loudness rows** with the measured figures, and an ADM's
  own declared loudness is shown where it states one.
- **Double-click a file to play it** (or stop it if it is playing).
- Open, Video and Binaural are icons now (hover for the name); bigger
  disclosure triangles; a slightly taller transport.
- Removing a file from the list asks first, the Delete key included.
- The object view folds away behind its triangle, and stays folded.

### Waveform caches

- **One folder per audio file instead of loose files.** A file's waveform
  cache is now `<file>.data/` beside it, not one sidecar per channel — a
  114-object ADM used to leave 115 files next to the master. Old caches are
  removed the first time a file is opened, so it rescans once.

### For testers

- **Custom:** in an EDL's Speaker Layout, change one speaker's output — the
  Monitor button should say Custom; pick the layout again and it should say
  its name.
- **Auro + Binaural:** open an Auro-3D master in the Preview, turn Binaural on,
  and check the rows stay at 12 while the monitor meters show two.
- **Drag bar:** widen and narrow the file list and check only the waveforms
  change width.

Everything else is as in 1.1.101.

[Back to the list of versions](#versions)

---

<a name="v1-1-101"></a>
## 1.1.101 — 2026-09-26

### Fades play exactly as they export

- **A clip fade you hear is now bit-for-bit the fade that exports.** Playback
  and export used to work a fade out two slightly different ways, so a null
  test of an export against what was monitored could leave residue across
  every fade. They now share one calculation, and the Test Suite proves it:
  linear, cosine and shaped fades, clip gain and crossfades all null to zero,
  sample for sample.
- **One small change you may notice:** a clip that runs past the end of its
  audio file now fades out where the clip ends, as the export always did.
  Playback used to fade it where the audio ran out.

### Fixed

- **Closing a Project, or quitting, while Tools > Run Test Suite was running
  could crash soundBlade.** It now stops the Test Suite first, then closes.

### For testers

- **Null test a fade:** export a passage with crossfades, and compare it with
  what you hear — there should be nothing left.
- **Play a busy EDL at a 512 buffer** (with your usual plug-ins) and, if you
  hear any clicks, send the log (`~/Library/Logs/soundBlade/soundBlade.log`) —
  the line "Playback under-runs this pass" says whether it was the disk or the
  CPU.

Everything else is as in 1.1.100.

[Back to the list of versions](#versions)

---

<a name="v1-1-100"></a>
## 1.1.100 — 2026-09-26

This release answers the latest round of tester reports.

### SRPs

- **Unlocked SRPs can be dragged again.** Before, a drag moved an SRP by a
  pixel at most and then stopped.
- **The SRP menu opens under the SRP** you right-clicked, not in the EDL's
  left margin.
- **SRPs are twice the size** and easier to grab; their labels are 15% larger,
  in black on a light box so they read over any waveform.
- **Setting an SRP clears the Edit Point** it was made at. A real time
  selection is left alone.

### Zoom

- **Zoom to Previous (⌘P) and Zoom to Next** now return to where you were,
  however many zooms back. They used to lose the position after a zoom or two
  and jump to the end of the EDL.
- A trackpad pinch is now one step in the zoom history, not dozens.

### Crossfades

- **The outgoing clip, its waveform and its green fade-out are no longer
  hidden** behind the incoming clip. Both fade curves are always visible.
- **The Edit Fade window now uses the timeline's colours**: fade-out green,
  fade-in red. They were the other way round.

### Source / Destination

- **Source and Destination work within one EDL and across two EDLs.** Only
  one EDL can be Source and one Destination at a time; setting a second EDL
  to Source clears the first.
- **Press S, D or N anywhere in an EDL** to set it — or the selected tracks'
  group — to Source, Destination or None. Ctrl+S / Ctrl+D / Ctrl+N work as
  before (they move the selected tracks to a new group first).
- **An EDL's role is shown by its border and a border round its name**, blue
  for Source and yellow for Destination, as well as the tracks' S/D buttons.
- **Replace / Insert** use a Source and Destination in the same EDL first,
  otherwise a Source EDL and a Destination EDL. If that is ambiguous they say
  which EDLs conflict and do nothing.
- **DDP export needs the selected EDL to hold its own Destination**; if the
  Destination is in another EDL, the message says which.
- **Solo Track no longer uses Ctrl+S** — that is Set Source.

### Also

- **New EDLs start with two tracks** in one Edit Group (was four).
- **Single Play Mode** — Application Settings > General. When ticked, starting
  playback in one EDL stops every other EDL that is playing, in every Project
  window. EDLs that are Play-Locked together still play together. Off by
  default.
- **With no Project open, ⌘N, ⌘O and ⌥A work** from the menus.

### For testers

- **S, D and N** in a single EDL and across two EDLs — watch the borders.
- **Single Play Mode** with two Project windows open.
- **SRPs on the smallest track height** — the larger handles may now be easy
  to grab by accident there.

Everything else is as in 1.1.99.

[Back to the list of versions](#versions)

---

<a name="v1-1-99"></a>
## 1.1.99 — 2026-09-26

### Fixed: playback could hear a plug-in out of time against the other tracks

- **A plug-in that reports its latency a moment after it starts was heard late
  in playback** by that latency, against every other track, for the whole of
  its Desk Event. Found with MAAT thEQblue: 1354 samples (14 ms at 96 kHz)
  late. 1.1.98 fixed the same thing in exports; this fixes what you hear.
- **How it is fixed:** every plug-in is now run briefly on silence as it
  loads, before it is played, so the latency it reports is the one it really
  has. Playback lines up from the first sample.

### Fixed: changing a plug-in while playing could slide the mix

- **Adding or removing a plug-in that has latency while playing** used to move
  the time alignment of the tracks under the audio — heard as a jump or a
  repeat.
- **A plug-in that changes its latency while playing** (for example switching
  an EQ into linear-phase mode) left that track out of time until something
  else rebuilt playback.
- **Both now resync instead:** playback fades out over a few milliseconds,
  stays silent while the timing is recalculated (about as long as the
  plug-in's latency — typically 10–40 ms), then fades back in, in time. The
  transport keeps running, so Play-Locked EDLs stay together. The log
  (`~/Library/Logs/soundBlade/soundBlade.log`) notes each resync.

### Also

- A plug-in may take a moment longer to load than before, because of the
  silent warm-up.

### For testers

- **Play an EDL with MAAT thEQblue (or any linear-phase EQ / look-ahead
  limiter) on one track** beside tracks without it, and listen for phasing or
  flamming — there should be none.
- **Add or remove a latent plug-in while playing:** you should hear a brief
  dip to silence and then the mix back in time, never a jump or a repeat.
- **If a heavy plug-in now loads noticeably slower**, please tell us which.

Everything else is as in 1.1.98.

[Back to the list of versions](#versions)

---

<a name="v1-1-98"></a>
## 1.1.98 — 2026-09-26

**Please update from 1.1.97.** It fixes an export problem in 1.1.97.

### Fixed: 1.1.97 could export part of a mix late

- **In 1.1.97, a plug-in that reports its latency a moment after it starts
  could be exported late by that latency** — across the whole of that
  plug-in's Desk Event. Found on a real export: MAAT thEQblue's section came
  out 1354 samples (14 ms at 96 kHz) late, while every other part of the file
  was correct. It did not happen every time, which is how it got through.
- **Only 1.1.97 is affected, and only exports made with Tools > Use Streaming
  Render ticked** — which was the default in 1.1.97. 1.1.96 and earlier, and
  any 1.1.97 export made with it unticked, are not affected.
- **If you exported with 1.1.97 using plug-ins that have latency** (linear-phase
  EQs, look-ahead limiters and the like), please export those again with 1.1.98.
- **How it is fixed:** when a plug-in's section ends, the streaming export
  checks the plug-in's latency again. If it changed, that export is thrown
  away and made again the previous way, which always handles it correctly —
  the export takes longer, and is never written wrong. The log
  (`~/Library/Logs/soundBlade/soundBlade.log`) names the plug-in when this
  happens.

### Streaming export (unchanged from 1.1.97)

- Still ON by default: exports render a second at a time, straight to disk,
  so memory stays flat however long the export.
- Untick **Tools > Use Streaming Render** to export the previous way; it is
  ticked again at the next launch.

### For testers

- **Re-export anything made with 1.1.97** that used plug-ins with latency, and
  compare if you still have the 1.1.97 file.
- **If the log says a plug-in "changed its reported latency"**, please tell us
  which plug-in — it is working correctly, but we would like to know which
  plug-ins do this.

Everything else is as in 1.1.97.

[Back to the list of versions](#versions)

---

<a name="v1-1-97"></a>
## 1.1.97 — 2026-09-25

Streaming export is now the default.

### Streaming export is ON by default

- **Exports now render a second at a time, straight to disk,** instead of
  building the whole programme in memory first. Memory use stays flat however
  long the export — an hour of 7.1.4 used to need over 8 GB before anything
  was written.
- **It prints the same file.** Besides the Test Suite's sample-for-sample
  comparisons, a real 27-minute album export at 96 kHz with six MAAT and SCC
  plug-ins across two Edit Groups (one with 1.4 seconds of latency) came out
  bit-identical to the previous export method. Where sample-rate conversion
  is involved the two agree to within -120 dBFS.
- **It covers** Export Sound File, Album Renders and stems written as one
  file — plug-ins, Edit Group plug-ins (including linked copies), the Master
  Bus chain, object panning, layout conversion, sample-rate conversion and
  dither.
- **Not yet covered**, and exported the previous way automatically: diffuse
  objects (Tools > Render Diffuse Objects), one file per track, Measure
  Loudness (including the loudness Export ADM measures), Run Null Test and
  Sync To Matching. The result is correct either way — only the memory use
  differs.
- **The way back:** untick **Tools > Use Streaming Render** to export the
  previous way. It is app-wide and not saved, so it is ticked again at the
  next launch. The log (`~/Library/Logs/soundBlade/soundBlade.log`) says which
  method made every export.
- **Streamlined since 1.1.96:** the streaming export's internal buffering
  now copies audio in blocks rather than sample by sample.

### For testers

- **Nothing to switch on** — just export as usual, and please report
  anything that sounds or measures different from earlier builds.
- **If an export seems wrong,** untick Tools > Use Streaming Render, export
  again, and send both files (or the difference you hear), the EDL and the
  log.
- **Plug-ins:** the streaming export keeps every plug-in in the export
  running at once. If one misbehaves, crashes or prints differently, please
  tell us which one.

Everything else is as in 1.1.96.

[Back to the list of versions](#versions)

---

<a name="v1-1-96"></a>
## 1.1.96 — 2026-09-25

A new way to export — a second at a time, straight to disk — ready to try, and a fix for plug-ins on very short Desk Events.

### Streaming export (new, off by default)

- **Tools > Use Streaming Render** exports a second at a time, all the way to
  disk, instead of building the whole programme in memory first. Memory use
  stays flat however long the export: an hour of 7.1.4 used to need over
  8 GB before anything was written.
- **It prints the same file.** Every export it covers has been compared
  against the existing export, sample for sample: identical, and within
  -120 dBFS where sample-rate conversion is involved (the converter rounds
  very slightly differently when fed in pieces).
- **It covers** Export Sound File, Album Renders and stems written as one
  file — plug-ins, Edit Group plug-ins (including linked copies), the Master
  Bus chain, object panning, layout conversion, sample-rate conversion and
  dither.
- **Not yet covered**, and exported the existing way even with the switch on:
  diffuse objects (Tools > Render Diffuse Objects), one file per track,
  Measure Loudness (including the loudness Export ADM measures), Run Null
  Test and Sync To Matching. The result is
  correct either way — only the memory use differs.
- **It is off by default** while it is tested. The switch is app-wide and not
  saved. The log (`~/Library/Logs/soundBlade/soundBlade.log`) says which
  method made every export, and why when the streaming one was not used.

### Fixed

- **A Desk Event shorter than its plug-in's latency printed the wrong audio.**
  A brief event carrying a high-latency plug-in (for example a linear-phase
  EQ over a fraction of a second) exported mostly silence where its processed
  audio belonged. It now prints what was monitored.

### For testers

- **Streaming export:** tick **Tools > Use Streaming Render** and export
  something long — an album EDL, a long ADM — then export the same thing with
  it unticked and compare the two files (or listen). Please report any
  difference, the EDL it came from, and the log.
- **Plug-ins:** the streaming export keeps every plug-in in the export
  running at once, where the existing export ran them one after another. If a
  plug-in misbehaves, crashes or prints differently with the switch on,
  please tell us which one.
- **Memory:** on a long export, Activity Monitor should show soundBlade's
  memory staying roughly level with the switch on, and climbing with it off.

Everything else is as in 1.1.95.

[Back to the list of versions](#versions)

---

<a name="v1-1-95"></a>
## 1.1.95 — 2026-09-25

Plug-ins in Edit Groups, plug-in latency, and playback that no longer drops out when the disk falls behind.

### Plug-ins in an Edit Group

- **A plug-in added to one track of a group now goes on that track only.** It
  used to be copied onto every track in the group.
- **To share a plug-in across the group, right-click it and tick "Share
  across Group".** A shared plug-in runs as ONE instance across every track
  in the group, so it glues them. Only shared plug-ins get the group-colour
  border, so glue and a track's own plug-in look different.
- **EDLs saved in earlier versions keep their glue.** A plug-in that sat
  identically on every track of a group opens shared, as it always ran.
- **A track joining a group keeps its own plug-ins** and gains the group's
  shared ones. Joining used to replace what the track already had.

### A shared plug-in that will not fit the group

- A stereo plug-in shared across a group wider than two channels (two stereo
  tracks, or three mono tracks) cannot run as one instance. It used to simply
  not run, and nothing said so.
- **soundBlade now asks.** It can run as **linked copies** — one set of
  controls, but each copy hears only its own tracks, so it will not glue the
  group the way one instance would — or **not run**. Until you answer it does
  not process; its latency is compensated either way.
- **The answer is saved with the EDL** and asked again if the group's width
  changes. To change it later, right-click the plug-in: **Run as Linked
  Copies**.
- **A plug-in you chose not to run has a red border** and reads
  "(not running)".
- **Export follows your answer.** It stops with a message if the question was
  never answered.

### Latency

- **Bypassing a Master Bus plug-in no longer shifts part of the bus out of
  time.** Its latency is kept whether it is bypassed or not, and bypassing
  and un-bypassing no longer click.

### Playback

- **Playback reads further ahead** (about a second) on files opened as one
  track per channel — ADMs, Auro-3D and multichannel masters — and keeps that
  read-ahead through edits made while playing.
- **When the read-ahead falls behind, the audio is read directly instead of
  dropping out.** Artist Connection clips are the exception: they stream, so
  a gap there is still silence.

### For testers

- **The red border.** Put two STEREO tracks (or three mono tracks) in one
  Edit Group. Add **MAAT thEQred** (or thEQblue, or SCC) to one track,
  right-click it and tick **Share across Group**. A moment later you should
  be asked whether to run it as linked copies. Choose **Don't Run**: the
  plug-in should turn red and read "(not running)". Right-click it and tick
  **Run as Linked Copies** to bring it back.
  - Two MONO tracks will NOT ask: that is two channels, which a stereo
    plug-in fits as one instance.
  - Apple's built-in AU effects usually accept any width, so they may never
    ask. If a plug-in never asks, please tell us which one.
- **Grouped EDLs from earlier versions:** please open one with glue plug-ins
  and check they still show the group-colour border (shared) and sound the
  same.
- **Dropouts:** if playback still breaks up, please send
  `~/Library/Logs/soundBlade/soundBlade.log`. It now also says how often the
  read-ahead fell behind.

Everything else is as in 1.1.94.

[Back to the list of versions](#versions)

---

<a name="v1-1-94"></a>
## 1.1.94 — 2026-09-24

One change to the Export window.

### Export exports the whole EDL

- **The Export window now always renders the whole EDL** — every track, the
  full length — whatever is selected. A time or clip selection used to crop
  the export, so a selection left over from editing could silently shorten a
  delivery.
- **To export only part of an EDL, use Export Selection**, which is
  unchanged.
- Create Tracks from Marks still splits the whole EDL into songs, and Round to
  still applies.

### A question for testers

- **Should Export render only the Destination tracks** (and say so when an EDL
  has none), or every track as it does now? Please tell us how you use it.

Everything else is as in 1.1.93.

[Back to the list of versions](#versions)

---

<a name="v1-1-93"></a>
## 1.1.93 — 2026-09-24

Export fixes and a better question at the end of every export.

### After an export: open it in an EDL

- **Every Sound File export now ends with: Open in EDL / Open in New EDL /
  No.** (It used to offer Open in Preview, and only after Create Tracks from
  Marks.)
- **Open in EDL** adds the render to the EDL it came from on new tracks — one
  per channel, "Export L" / "Export R" for stereo — with each file placed at
  the time it was rendered from (each song at its Start mark). So the render
  sits **aligned under the original**, ready to compare. One Undo removes it.
- **Open in New EDL** does the same in a new EDL at the bottom of the Project,
  with the same sample rate and speaker layout, so the times still line up.
- Only the **EDL's own layout** is placed (the Stereo files of a stereo EDL);
  with only Stems exported, the stems are placed instead.

### Edit works with the EDL's own layout

- **Edit** (put the rendered result back in place of what was exported) was
  greyed out whenever any layout was ticked — including the EDL's own, which
  the window opens on. It is now available when the only layout ticked is the
  EDL's own (or Stems). Another layout, several, or Multiple Export still turn
  it off, and its tooltip now says why.

### File names

- With name tags in use, a whole-EDL or selection export named its file with
  every tag twice — `Mix_2026-09-24_2026-09-24`. Fixed.

### The silent right channel (from 1.1.91's known issues)

- **No longer reproduces.** A Stereo layout export of the EDL that showed it
  now prints both channels, with plug-ins on and off, and the in-app Test
  Suite prints every group arrangement correctly. The cause was never pinned
  down, so every export now **logs** what each plug-in in the print did to
  each channel — if a silent channel ever comes back, please send the log
  (`~/Library/Logs/soundBlade/soundBlade.log`) with it.

### For testers

1. Export (with and without Create Tracks from Marks), choose **Open in EDL**,
   and check the new tracks line up with the original. Undo removes them.
2. Try **Open in New EDL** and Zoom Lock it against the source.
3. Export a stereo EDL as Stereo with **Edit** ticked.
4. Export with a name template that includes the Date — it should appear once.

[Back to the list of versions](#versions)

---

<a name="v1-1-92"></a>
## 1.1.92 — 2026-09-24

Two things testers asked for.

### Track meters show every channel

- A track playing an **interleaved multichannel file** (stereo, 5.1, 7.1.4 —
  up to 16 channels) now meters **each channel as its own bar** in the track's
  fader column, left to right in channel order. It used to show one bar, the
  loudest channel.
- The peak number and the red over indicator still report the loudest
  channel. Hover the meter to see the channels listed — by the file's own
  speaker names where it declares them, Ch 1–N otherwise.
- Mono tracks, files wider than 16 channels, and the Mini/Tiny track heights
  keep the single bar.

### Cut and paste between Projects

- **One clipboard for the whole app.** Copy or Cut clips in any EDL of any
  Project window and Paste into an EDL in another Project — the clips, their
  Desk Event plug-ins and their layout across tracks come with them. It used
  to work only between EDLs of the same Project.

### Known issue — unchanged from 1.1.91

- **A Stereo layout export of an EDL with Edit Groups and group-shared
  plug-ins can come out with the RIGHT channel silent.** The render path
  itself is now tested and sound in every arrangement we could build; it is
  looking specific to certain plug-ins in the print. Check any such export
  before delivering it.

### For testers

1. Play a stereo or multichannel file on one track and watch each channel's
   bar; hover the meter for the channel list.
2. Copy clips in one Project window, open or switch to another Project, and
   Paste.

[Back to the list of versions](#versions)

---

<a name="v1-1-91"></a>
## 1.1.91 — 2026-09-24

DDEX arrives in the Preview, plus layout and header fixes.

### DDEX (ERN 4.3) — in the Preview

- **Export... now asks: CSV or DDEX.** DDEX writes an ERN 4.3 release
  message from the list: each file is one recording, in list order, its
  metadata record the track and the album record the release. Files that
  share a **Track** number are one song in different layouts, and each layout
  is its own recording with its own ISRC.
- **Before it writes**, it checks everything a release needs and lists what is
  missing — nothing is written until it is complete: album title, artist,
  UPC, label, genre and release date (YYYY-MM-DD); per file a title, an ISRC
  and a Layout; no ISRC used twice.
- A small dialog asks for the sender and recipient, each with an **optional
  DDEX Party ID**. Without one the message carries `PADPIDAUNASSIGNED` — fine
  for internal use; a store will require a real one. **"Copy audio and artwork
  into the delivery folder"** is off unless you tick it; off, the message
  points at the files where they are.
- **Import... now also takes a DDEX `.xml`** — even on an empty list. It checks
  the message and every file it names (references, UPC and ISRC check digits,
  track order, files present, MD5 checksums, channels / rate / bit depth /
  duration against what the message says) and shows a **report** you can
  save. **Add to List** — only when there are no errors — brings the files in,
  in release order, and writes a metadata record beside each.
- **Edit Metadata** has a new **Track** and **Layout** row. Layout (Stereo,
  5.1, 7.1.4, Auro-3D, Auro-Cx, Binaural) fills itself only when the file says
  what it is — an Auro-3D carrier, an Auro-Cx file, a 5.1 or 7.1.4 channel
  mask. A binaural file is two channels like stereo, so that one is yours to
  set.
- Mark Info and the Export window get DDEX next.

### Preview

- **One button row**: Open EDL and Assemble Album sit after Export..., narrower;
  **Source** is under the Desk meters, **Monitor** under the monitor meters,
  **Binaural** between them, all full height. The window cannot be made so
  narrow that they overlap.

### EDL header

- The **compact-header triangle** now shows only on an EDL below the top one
  with Zoom Lock on — never on the top EDL or when only one EDL is open — and
  always while the header is compact, so it can be expanded again. It sits
  left of Sample Rate, above the Tracks triangle, and does not move.

### Known issue — please report what you see

- **A Stereo layout export of an EDL with Edit Groups and group-shared
  plug-ins can come out with the RIGHT channel silent.** Seen on one test EDL
  (two groups of two mono tracks, group-shared EQs, Create Tracks from Marks).
  The cause is not found yet. Check any such export before delivering it.

### For testers

1. **Export DDEX** from the Preview with Copy ticked and unticked; then
   **Import** the `.xml` you wrote — it should verify with no errors.
2. Try **Import** on a message whose files are missing, or edit a checksum in
   the `.xml`, and see the report catch it.
3. Set **Track** and **Layout** in Edit Metadata and check a song's layouts
   come out as separate recordings.
4. Check the Preview's button row at a narrow and a wide window.

[Back to the list of versions](#versions)

---

<a name="v1-1-90"></a>
## 1.1.90 — 2026-09-23

A small follow-up to 1.1.89.

### Cover images

- **An X to remove a chosen cover.** In Mark Info and in the Preview, a cover
  image you chose now shows a small **X** in its top-right corner — click it to
  remove the image. A file's own artwork, or a `cover.jpg` beside it, is not
  something the Preview can delete, so it shows no X.

Everything else is as in 1.1.89 — see its notes for the metadata, Mark Info,
Preview and compact-header work.

### For testers

1. **Choose a cover** in Mark Info and in the Preview, then remove it with the
   X.
2. The 1.1.89 checklist still applies: import a metadata sheet into Mark Info,
   export with Create Tracks from Marks, and check the files in the Preview.

[Back to the list of versions](#versions)

---

<a name="v1-1-89"></a>
## 1.1.89 — 2026-09-23

Metadata you can gather, import and deliver: a metadata record beside every file, import from CSV or Excel into Mark Info and the Preview, a cover image for the album, and exported songs that carry it all with them. Plus a compact EDL header for locked EDLs.

### Metadata

- **Metadata is kept beside the file, not in it.** Each audio file can have a
  small record beside it (`<file>.sbmeta.xml`) holding its title, artist,
  album, genre, ISRC, ISWC — and every other field a sheet brings, such as
  Composers, Lyricist or Work Title. **Save** in the metadata window writes
  the record and never changes the audio file. **Save to File** also writes
  the tags into the file, and with **ISRC Only** ticked it writes just the ISRC
  and leaves every other tag in the file as it was.

- **Import from CSV or Excel.** The metadata window's **Import…**, the
  Preview's **Import…** and Mark Info's **Import Metadata…** read a CSV or an
  Excel workbook (.xlsx). The track list is found wherever it is — headers on
  row 1 or row 3, on whichever sheet holds the tracks — and the Pure Audio
  Streaming template's example row is skipped. Each row is matched to its song
  or file by ISRC, else by track number, and **you review the matches before
  anything is written**. Anything that cannot be matched with certainty — two
  rows numbered 1, say — is left for you to choose rather than guessed.

- **Damage from spreadsheets is caught.** A UPC a spreadsheet turned into
  `6.09E+11` has lost its digits and is refused, with the reason. Accented
  text garbled by the wrong encoding (`sch√∂ne`) is repaired and reported. A
  date like `3/4/26`, which could be either day or month first, is refused
  rather than guessed; `8/21/26` is read as 2026-08-21.

- **ISWC and UPC are recognised, and their check digits verified.** A column
  of codes with no header is recognised as ISRCs or ISWCs by their shape.

- **Export.** Mark Info's **Export Metadata…** and the Preview's **Export…**
  write a CSV that Import reads back unchanged — for a label to fill in or
  check.

### Mark Info

- **Import Metadata… / Export Metadata…** onto the songs (the Start marks).
  Titles, artists and ISRCs fill the Mark Info fields; every other column is
  kept with the song, saved in the EDL. The whole import is **one Undo**.
- **A cover image for the album** — click the square beside Album and Artist.
- **Create Tracks from Marks** writes each song with its tags as before, and
  now also its metadata record beside it, copies the cover into the folder,
  and **asks whether to open the songs in the Preview** to check them.

### Preview

- **A triangle on each file** opens a line under it with the file's metadata:
  title, artist, ISRC, ISWC. Click again to close it.
- **The album cover** is shown beside the loudness read-outs: the file's own
  artwork, else the image you choose (click the square), else a `cover.jpg`
  beside the file. Under it: the image's size, its data size and where it came
  from.
- **Import…** and **Export…** beside Edit Metadata; **Open EDL** and
  **Assemble Album** moved to the right end of the row.
- The metadata window steps through the list with **Prev / Next**, and **Save**
  turns yellow while there are unsaved edits.

### EDL header

- **Compact header.** A triangle beside each EDL's name folds its header down
  to the name, Sample Rate, the locks, the overview and the ruler, and gives the
  rest to the tracks. **Turning on Zoom Lock does this automatically** for every
  EDL but the top one, which keeps the time display and transport the others
  follow.

### For testers

1. **Import the Pure Audio Streaming workbook** into Mark Info on an EDL with
   Start marks, review the matches, and check the titles and ISRCs. Undo once.
2. **Export with Create Tracks from Marks** and look for the `.sbmeta.xml`
   files and the cover beside the songs; say yes to opening them in the
   Preview and open a row's triangle.
3. **Zoom Lock two EDLs** and check the lower one folds and the top one keeps
   its transport.

None of this has had a listening test here, and none of it changes audio. The
sheet reader and matching were checked against real label sheets; the rest is
covered by the in-app test suite (Tools > Run Test Suite: "Metadata record" and
"Metadata import") and by nothing else.

[Back to the list of versions](#versions)

---

<a name="v1-1-88"></a>
## 1.1.88 — 2026-09-22

Speaker naming in SMPTE or ITU-R, a Room view seen from the listener's seat, diffuse objects heard as diffuse, and ADM object timing read correctly. This release also carries the playback corrections prepared as 1.1.87, which was withdrawn before most testers received it.

### Read this first

**1.1.87 was withdrawn** after a build of the Sonic Reference Player made from
the same engine work broke up badly on playback. The cause was never
reproduced, and the leading explanation is another application taking the
audio device rather than anything in soundBlade. This release carries that
engine work.

**If you hear the audio break up, please report it**, with the machine, the
interface, the device buffer size, the sample rate, and whether 1.1.86 does the
same on the same EDL. `~/Library/Logs/soundBlade/soundBlade.log` records
under-runs and their cause; please attach it.

### Speakers

- **Speaker naming: SMPTE or ITU-R.** Speakers can be named the familiar way
  (L R C LFE Lss Rss Ltf …) or by ITU-R BS.2051 position (M+030 M-030 M+000
  LFE M+090 U+045 …). Set it with **Naming** in **Project Settings >
  Speakers**; changing it refreshes every EDL in the Project. An EDL can also
  be set on its own in its **Speaker Layout** dialog, and the Preview in its
  own. It changes labels only — never routing, audio, or anything written to
  a file. The Desk's master strip always keeps SMPTE names; the Monitor meters
  follow the setting.

- **A file that names its channels is believed.** A WAV or FLAC that declares
  its speakers (its channel mask) now gets those names in the Preview, and its
  layout comes from the declaration instead of being guessed from the channel
  count — the only way to tell ten channels of 7.1.2 from ten of 5.1.4. Each
  named channel also plays to the speaker it names, so a WAV-order 7.1 — rears
  before sides, as every WAV and FLAC 7.1 is — reaches the right speakers.

- **A 5.1.4 was shown and played as 7.1.2 in the Preview**, including a 5.1.4
  Auro decode. Fixed.

- **The Preview's Speaker Layout dialog** now applies a change to a single
  speaker's output. Before, only picking a whole layout took effect.

- **Drag the playhead line** down the Preview's Overview column to set where
  playback starts. While playing, it restarts from the new point when you let
  go.

- **The Preview's monitor meters scroll** when they do not all fit beside the
  fader, as the master meters beside them do. A 7.1.4 monitor used to be cut
  off unless the window was widened.

### Object audio

- **The Room view is seen from the listener's seat.** The front of the room is
  now the far wall and the rear the near one, looking down towards the front
  as from a theatre seat, with **FRONT** marked on the front wall under the
  centre speaker. It used to be drawn back to front. The flat Front and Side
  views were corrected the same way. Dragging still turns the room with the
  side nearest you following the mouse.

- **Diffuse objects sound diffuse.** An object an ADM declares as diffuse is
  now rendered that way — decorrelated across the speakers — instead of as a
  hard point. This matters on real masters: two commercial Atmos releases
  tested here declare most of their objects fully diffuse. It applies to
  playback, export and Measure Loudness alike, so what you print is what you
  monitored. **On by default**; Tools > Render Diffuse Objects turns it off
  for comparison.

- **An imported ADM keeps its objects' size.** Width, height, depth, diffuse
  and divergence were read from the file and then dropped on the way into the
  timeline, and anything written back out replaced the originals with zeros.
  They now survive.

- **Object moves happen when the file says they do.** An ADM states where an
  object arrives and how long the move takes; soundBlade read that as when the
  move begins, putting every imported trajectory up to one metadata block
  early. A move the file marks as quick-then-hold now moves over the stated
  time and holds, instead of being smeared across the whole block.

- **A moving object no longer steps**, and its pan follows its audio (from
  1.1.87). Position now updates every 64 samples with a ramp between, instead
  of once per audio block — at a 1024-sample buffer that was a click every
  10 ms. And with a latent plug-in in the EDL the pan no longer runs ahead of
  the sound. Measure Loudness pans moving objects properly too.

### Playback (from 1.1.87)

- **Nothing left over when the playhead jumps.** Pressing Play, seeking or
  looping could begin with a fragment of whatever was last heard, even with
  every plug-in muted. The delay lines and the plug-ins' own buffers are now
  cleared at every jump.

- **A Desk Event starts and ends on its own sample**, instead of being heard
  for the whole of any audio block its span touched.

- **Playback and export agree about time** to the sample.

### Edit Groups (from 1.1.87)

- **"Mute all plug-ins" applies to the whole Edit Group.** Option-clicking P on
  a member other than the first used to light the button and mute nothing.

- **A group plug-in that cannot run now says so in the log.** Running it as
  linked copies, the way the Master Bus already does, is not built yet.

### For testers

1. **Does the audio break up?** See "Read this first" — a clean report is as
   useful as a broken one.
2. **Try Naming** in Project Settings > Speakers and in an EDL's Speaker Layout
   dialog, and check the labels change everywhere you expect and nowhere else.
3. **Open the Room view** and check the room reads the right way round — front
   far, L on the left — and that the speakers sit where you expect.
4. **Play an ADM with diffuse or moving objects** and compare against 1.1.86.
5. **Listen across a Desk Event's start and end**, with Play started from
   inside the span.

None of this has had a listening test here. The object, timing and naming work
is covered by the in-app test suite (Tools > Run Test Suite), and by nothing
else.

[Back to the list of versions](#versions)

---

<a name="v1-1-87"></a>
## 1.1.87 — 2026-09-21

Audio correctness: nothing left over when you press Play, Desk Events that start and end on the sample you put them on, and an object panner that moves smoothly and prints what you monitored.

### Playback

- **Nothing left over when the playhead jumps.** Every delay line soundBlade
  uses to keep tracks in time was fed only while the transport rolled, and
  never cleared — so pressing Play, seeking, or looping began with a fragment
  of whatever was last playing, for as long as the EDL's plug-in latency.
  It was audible with **every plug-in muted**, because those lines run whether
  the plug-ins do or not, and it never registered as a dropout, because
  nothing had fallen behind. Both the delay lines and the plug-ins' own
  internal buffers are now cleared at a transport jump.

- **A Desk Event starts and ends on its own sample.** A plug-in used to be
  heard for the whole of any audio block its span touched, so an event
  beginning part-way through a block was audible up to a block early, applied
  to audio the plug-in had never been fed. It is now fed exactly its span's
  samples and heard on exactly its span's samples — the same rule an export
  has always followed.

- **Playback and export now agree about time.** Playback rounded positions
  down to the sample where an export rounds to the nearest, so a clip or a
  Desk Event could sit one sample earlier in what you heard than in what you
  printed.

### Objects

- **A moving object no longer steps.** The panner read an object's position
  once per audio block and held one gain across the whole of it — at a
  1024-sample buffer that is a step every 10 ms, and each step is a click.
  Position and gain now update every 64 samples and ramp between, the same
  resolution recorded plug-in automation already used. A stationary object
  costs exactly what it did before.

- **The pan follows its audio.** Live, an object's position was read at the
  transport's time while the audio it applied to had already been delayed for
  plug-in latency compensation — so with a latent plug-in anywhere in the EDL
  the pan ran ahead of the sound. An export never had this, so the two
  disagreed.

- **Measure Loudness pans objects properly too.** It was taking each block's
  midpoint position and holding it, measuring a moving object somewhere it
  never actually was.

### Edit Groups

- **"Mute all plug-ins" applies to the whole Edit Group.** It was per track,
  while a group's shared plug-in only ever consults the group's first track —
  so Option-clicking P on any other member lit the button and muted nothing.
  To mute one track's plug-ins on their own, take it out of the group first.

- **A group plug-in that cannot run now says so.** If a plug-in cannot be
  configured for the total width of the tracks in a group — a stereo plug-in
  across three stereo tracks needs six channels — soundBlade could not run it
  and said nothing at all, leaving the group unprocessed. It is now recorded
  in the log. **The real fix, running it as linked copies the way the Master
  Bus already does, is not built yet.**

### For testers

- **Please listen across a Desk Event's start and end**, with and without
  "mute all plug-ins", and with Play started from inside an event's span.
  That is the area this release changes most.

- **Objects are worth a listen on a fast move** — a hard pan across the room
  should sound continuous now.

- **This release is verified by the in-app test suite** (Tools > Run Test
  Suite), which grew 21 new checks for exactly these behaviours and passes
  260 of 260 on the fixtures here. It has **not** had a listening test, which
  is what the two points above are asking for.

- **Known and not fixed:** clicking on playback with several plug-in-bearing
  tracks at a 1024-sample buffer is a CPU limit, not a defect — the callback
  misses its deadline while the plug-ins process. Raising the device buffer
  size is the workaround. Please report whether 2048 clears it for you.

[Back to the list of versions](#versions)

---

<a name="v1-1-86"></a>
## 1.1.86 — 2026-09-21

Auro-Cx: soundBlade now decodes Auro's coded bitstream, not only the carrier.

### Auro-Cx

- **Auro-Cx files decode and play.** This is a different format from the
  Auro-3D carrier soundBlade already read: a carrier is ordinary PCM with its
  height channels hidden in the low bits, while **Auro-Cx is a coded
  bitstream** in an `a3ds` track described by an `acxd` box. It means nothing
  until a Cx decoder has had it, and uses a different Auro engine.

  Nothing in macOS can open one of these — both AVFoundation and CoreAudio
  refuse the container outright — so this uses Auro's own MP4 parser and Cx
  engine end to end.

- **The layout comes from the file.** A 5.1 Auro-Cx master opens as 5.1, a
  7.1.4 one as 7.1.4. The decoder is asked what the content *is*, rather than
  what it can render to.

- **Seeking is exact.** A seek re-primes the decoder from 32 access units
  earlier, a figure measured against real files rather than guessed — restarts
  were bit-identical at every point tested.

### Preview

- **The monitor meters show the right number straight away.** They were correct
  but drawn inside a strip still sized for the previous count, so a window
  opened before its file had a layout showed two meters until something
  triggered a resize.

- **A file shows its own layout on the first view.** Selecting a file set the
  monitor layout but did not push it to the bus until the *second* time that
  file was selected — so the first view could meter against nothing.

- **The Monitor read-out says when the device has narrowed it**, as
  `5.1 → Stereo`. A device with too few outputs has always been monitored
  correctly on what it has; it just never said so, which read as a fault.

### For testers

- **Auro-Cx is new and has had one day of use.** The decode itself was measured
  — seeks bit-identical, the layout read from the stream — but everything
  around it is a day old. Anything that sounds wrong is worth reporting at once.

- **A note for Auro:** the Cx components are present in the SDK drop we hold and
  work as documented. What is not clear from the package is whether our existing
  agreement covers *shipping* them — the drop is named "Passthrough", which is a
  narrower thing than decoding. We would like that confirmed.

[Back to the list of versions](#versions)

---

<a name="v1-1-85"></a>
## 1.1.85 — 2026-09-20

Small corrections to 1.1.84's MP4 support, found by testing it against a real set of video files.

### MP4

- **Dolby soundtracks are named properly.** A 5.1 film mix delivered as Dolby
  Digital Plus was labelled `EC-3`, which is its four-character code and tells
  you nothing. Rows now read **Dolby Digital Plus** and **Dolby Digital**, and
  HE-AAC is named too. A codec still not recognised keeps its four-CC — that
  says we can read it and did not recognise the name, rather than inventing
  one.

- **A lossless track reports the depth it was written at.** A 24-bit FLAC
  inside an MP4 read `FLAC 48/32` — 32 being the depth soundBlade decodes to,
  which describes the reader rather than your file. It now reads `FLAC 48/24`,
  taken from what the file itself declares. This matters beyond the row, since
  that figure is what the export dialog defaults to.

  A lossy track has no source depth to report, so it still says "lossy" with no
  number.

### Test Suite

- **Escape stops a run, from any window.** A run that had opened a dialog, or
  simply left you working elsewhere, could previously only be stopped by
  finding the Test Suite window again.

- **Details… documents the audio-file fixtures.** It described EDL fixtures
  only, so the Auro-3D and MP4 sections — which look for media files in the
  folder rather than `.edl`s — gave no hint what to put there. It now says what
  each looks for, and suggests the spread of codecs worth having in a
  `Video Files` folder.

- **The MP4 section checks every video file in the folder**, not the first one
  it finds. The container holds different codecs behind one extension, so one
  file leaves the others untested.

[Back to the list of versions](#versions)

---

<a name="v1-1-84"></a>
## 1.1.84 — 2026-09-20

Audio out of video files. An MP4 opens like any other master — including one with an Auro-3D carrier inside it — and brings its picture with it.

### MP4 and video files

- **An MP4 can be opened or dropped like any other audio file.** Raw PCM, FLAC
  and ALAC inside an MP4 are read **bit-exactly**: nothing on the path converts
  through floating point, which is what lets an Auro-3D carrier survive inside
  one. AAC is supported too and is **labelled "lossy"** on the file row, since
  what it cannot be is a master.

- **The file row names the codec rather than the extension.** ".wav" tells you
  a file is PCM; ".mp4" tells you nothing, and the three masters this was built
  against are PCM, FLAC and AAC behind that same extension. So a row reads
  `PCM 48/24`, `FLAC 96/24` or `AAC 48 lossy`.

- **An Auro-3D carrier inside an MP4 decodes.** It was detected and not
  decoded — the row said "Auro-3D 7.1.4" while eight undecoded carrier channels
  played into a twelve-wide bus with the four height meters silent.

- **Opening a movie brings its picture.** The video window opens on its own,
  already pointed at the file, instead of coming up empty because nothing had
  set the EDL's video. Set Video File also no longer imports a movie's audio a
  second time when it is already in the EDL.

- **A movie sits at its own start timecode.** Picture used to play from zero
  always, so TV material starting at 01:00:00:00 put its audio an hour in — as
  it should — while the picture ran an hour early. The timeline stays absolute
  and the movie moves to meet it.

  Movies that declare no start timecode are unchanged.

- **Channel names come from the file.** An MP4 that declares what its channels
  are gets real speaker names; one that declares nothing gets `Ch 1..N`, as
  before. Nothing is reordered — a file that lists rears before sides keeps that
  order, and the Out column re-patches it if you want otherwise.

### Editing

- **A file with a timestamp lands on it.** A BWF's Time Offset says where the
  recording belongs, and a set of stems now drops into sync in one gesture
  rather than needing Shift held.

  **Shift has swapped jobs**: hold it to place a timestamped file at the drop
  position instead. Files without a timestamp are unaffected.

### Preview

- **Binaural is a button you can see**, under the loudness read-outs, lit when
  it is on. It was a checkbox positioned past the edge of its column — invisible
  since the day it was added — so only the menu item ever worked. The Monitor
  read-out also says `7.1.4 → Binaural` while it is on: binaural monitoring is a
  stereo pair, so two monitor meters beside a box reading "7.1.4" looked exactly
  like a fault and was not one.

  The item has left the monitor menu, since the button replaces it.

### For testers

- MP4 support is new. The decode itself was checked against independent
  decoders — raw PCM against the file's own bytes, FLAC against ffmpeg — and
  seeking is sample-exact, but **the reader has had one day of use**. Anything
  that sounds wrong in an MP4 is worth reporting straight away.

- **A movie's start timecode has never been exercised**, because no file to
  hand carries one. It is written so that any doubt leaves the picture where it
  has always been, but a movie that really starts at 01:00:00:00 would be a
  valuable thing to try.

- A FLAC inside an MP4 reports its bit depth as 32, which is the depth it is
  decoded to rather than the depth it was written at. Cosmetic today; it will be
  read properly from the file.

[Back to the list of versions](#versions)

---

<a name="v1-1-83"></a>
## 1.1.83 — 2026-09-20

Recording, the Preview window, and the two Edit Fade Mode items from 1.1.82 that were not actually fixed.

### Recording

- **Record-enable belongs to the EDL you clicked it in.** Pressing Record lit
  the button on every open EDL, because the arm state was held once for the
  whole Project window. It is now per EDL: only the one you clicked is armed,
  Play in any other is an ordinary Play, and a newly opened EDL starts idle
  rather than inheriting somebody else's arm.

  There is still one recorder, so a take already running blocks a second one.

### Preview

- **Play stops at the end of the file.** It used to run off the end into empty
  timeline.

- **Loop works.** It repeats from wherever you started playing to the end of
  the master. The two were one fault: nothing armed an end point, so there was
  neither anything to stop at nor anything to repeat.

- **Finishing a pass returns to where that pass started**, not to zero — so a
  time you type into the read-out is a start point you can play again. Play
  from the top and it still comes back to the top.

- **A playhead over the waveforms.** The Overview column now draws a vertical
  line at the transport position, one per row, so the layout reads as a single
  position across every channel. It shows while stopped too, marking where the
  next Play will begin.

- **The Sonic Studio wordmark** now appears in the Preview window, left of the
  time read-out, as it does in the Sonic Reference Player.

- The Loop button's tooltip now says what it does in this window.

### Edit Fade Mode

- **Lock Sound: the sound really does stay put now.** 1.1.82 stopped the model
  moving it, and the audio still appeared to slide the moment you released the
  mouse — because Auto Zoom re-centred the pane on the edit point you had just
  moved, which slid the waveform under a re-centred fade marker.

  Auto Zoom now re-frames when a fade's **duration** changes, which is what it
  is for, and leaves the window alone while you move an edit point through
  fixed audio. You see the fade move across a stationary waveform.

- **Leaving EFM restores the zoom and position for real.** 1.1.82 restored a
  value that mirrors the scroll rather than the scroll itself, so nothing
  moved. It now puts the view back whether you leave with OK, Cancel, or by
  closing the mode.

---

### For testers

Worth exercising, in this order:

1. **Two EDLs open.** Record in one — only that transport should blink. Play
   the other: ordinary play, no take, no red tracks.
2. **Preview:** play a file to the end; it should stop and return to where you
   started it. Type a time in the read-out, play, let it finish, play again —
   it should start from your time both times.
3. **Preview Loop:** on, play, confirm it repeats; off mid-pass, confirm it
   stops at the end.
4. **EFM with Auto Zoom on:** Lock Sound on, drag the edit point, release. The
   waveform must not move. Then leave EFM and check the timeline is exactly
   where you left it — try OK, Cancel and closing the mode.

Untested here beyond a build: nothing in this release has been run by anyone
but the developer and Jon.

[Back to the list of versions](#versions)

---

<a name="v1-1-82"></a>
## 1.1.82 — 2026-09-20

Five fixes from tester reports: recording, Edit Fade Mode, and what the playhead does when you stop.

### Recording

- **A take now lands on the track it was recorded from.** Takes used to arrive
  on their own new track underneath, which meant arming four tracks and
  rolling produced four more tracks to move and tidy up. The take goes back
  where you recorded it.

  Where each clip sits is unchanged — still placed against the measured round
  trip, and a punched pass still becomes one clip per window.

- **Stopping a take is now visible immediately.** An armed track blinks red
  and a rolling one is solid, but on stop the button went on showing the same
  bright red for a fifth of a second, so "recording" and "armed" briefly
  looked identical. The blink now starts on its dim phase the moment a take
  ends.

  Note the track **stays armed** after a take — that is deliberate, and it is
  how you record another one. It goes on blinking red until you disarm it.

### Edit Fade Mode

- **Leaving EFM puts the timeline back exactly where it was.** Opening EFM
  re-frames the view around the edit you are working on, which is right while
  you are in it — and left you somewhere you did not choose when you came
  back. Zoom and position are now restored on exit, whether you leave with OK,
  Cancel, or by closing the mode.

- **Lock Sound now moves the fade and leaves the sound alone**, on the fade-in
  side. Moving the edit point with Lock Sound on used to trim the front of the
  incoming clip — the audio stayed where it was, but the clip's start moved
  with it, which changed what the crossfade had to work with. Now only the
  fade moves: the clip is untouched, the edit point slides within it, and the
  offset between the two fades changes to match.

  With Lock Sound **off**, the behaviour is unchanged: the whole incoming clip
  ripples with its audio, and everything after it moves too.

### Transport

- **Stop leaves the playhead where you stopped.** It used to jump back to
  where playback started. That was asked for on the understanding that play
  always starts from the Edit Point — which it does, until you set an Edit
  Point and then start somewhere else, at which point the playhead landed in a
  third place that was neither.

  With **Edit Point to Playhead** on, the Edit Point is still dropped at the
  playhead when you stop, so the two stay together.

---

### For testers

All five came from your reports. Two of them change what an edit or a take
actually does, so they are worth a deliberate first try rather than a glance:

- **Record onto an armed track** and check the take lands on that track, at
  the right place.
- **Lock Sound on the fade-in side** — move the edit point and confirm the
  clip does not move, only the fade.

Still open from the same list: **record-enable spans every EDL, but a take is
still captured from one**. Arming tracks in two EDLs and pressing Play records
one of them. That is a real limitation and it is next, once single-EDL
recording has been confirmed end to end.

[Back to the list of versions](#versions)

---

<a name="v1-1-81"></a>
## 1.1.81 — 2026-09-20

Audio correctness. Several faults in muting, the master strip and binaural monitoring that have been there a long time, found by using the Preview window hard for a day. Everything here is in the audio path, so it is worth a listen rather than a glance.

### Muting

- **Fixed: muting tracks of a multichannel master made noise that would not
  stop.** Mute all the tracks of a decoded Auro or ADM master, unmute a few,
  and it produced noise until you stopped and started the transport.

  Every channel of one file shares a single decode, which holds one position
  at a time and assumes all its channels read in step. Muting a track stopped
  it reading at all, which broke that lockstep — the remaining channels got
  audio from the wrong place in the file. Perfectly valid samples, from
  entirely the wrong position, which is why it sounded like noise. A muted
  track now keeps reading and is silenced by gain instead.

- **Fixed: mute and unmute clicked.** A track mute was not a gain at all — it
  simply stopped the audio, full scale to zero in one sample, and back again on
  unmute. Mute is now part of the same gain as the track fader and ramps across
  a block. The **master strip's** mute and fader did the same and now ramp too,
  so a fast fader move no longer steps.

- **Fixed: muting a master channel could produce garbage.** Master channel
  settings are created the first time you touch a channel, and creating one
  moved every other channel's settings in memory while the audio engine was
  reading them. Muting a channel you had not touched before could leave it
  taking its level from freed memory. Most likely after muting everything at
  once, which creates the most.

- **Fixed: muting master channel 1 stopped the whole Master Bus plug-in
  chain** — for every channel, not just that one. Soloing any other channel did
  the same. The plug-ins stopped receiving audio and then resumed from stale
  state.

### Binaural monitoring

- **Fixed: binaural clipped, loudly.** Every speaker was summed into the two
  ears at full level, so eleven speakers of a 7.1.4 master stacked up about
  10 dB hotter than the same programme on speakers. It now uses the same
  BS.775 balance the normal fold uses — fronts ahead, centre and surrounds
  behind — with headroom to match.

- **Fixed: LFE was summed into both ears at full level.** An LFE channel is
  carried around 10 dB hot by convention, so this alone overloaded. It is now
  dropped, which is what the normal fold has always done for a target with no
  LFE, and what BS.775 specifies.

- **Fixed: the other channels played underneath the binaural pair** in some
  configurations, instead of being replaced by it.

- **New: choose the binaural renderer** — **Auro** or **SOFA (HRTF)** — in
  Project Settings > Speakers. Auro is the default: it is a renderer tuned for
  this, and Auro's own encoder offers the same path. SOFA is our HRTF
  convolution and handles any layout, including ones Auro does not carry; if
  the Source layout is one Auro cannot render, soundBlade falls back to SOFA
  and says so.

  An Auro master always uses Auro's renderer whatever this is set to — it is
  already binaural by the time it is decoded.

### Also

- **Fixed: opening a 7.1.4 WAV tripped an assertion.** The Auro probe treated
  any wide file as a possible carrier; a carrier is 5.1 or 7.1 PCM, and a
  12-channel file is already discrete.

- **Nothing that reaches the audio device can now be a NaN.** If anything
  upstream produces one, the block is silenced rather than played — non-finite
  audio comes out as full-scale noise, which on headphones is dangerous.

- **Fixed: audio-thread allocations.** Three places allocated memory while
  audio was running whenever the channel count changed.

### Preview window

- **Resizing gives the space to the file list and the object viewer**, and
  keeps the channel list the size it needs. The extra width was going to the
  channel list, where it had nothing to do with it.
- **Click a row's Out column to send it to a different output.** It shows the
  output it goes to, and remembers it. Works for an unlabelled multichannel
  master too, which previously could not be re-patched at all.
- **The playing file is white in the list**, and each row shows its format and
  Auro tag right-aligned.
- **Fixed: clicking through files could hang for seconds at a time**, and in
  Debug builds triggered assertions. Selecting a file killed the previous
  file's parse and overview scan by force when they did not stop in time.

[Back to the list of versions](#versions)

---

<a name="v1-1-80"></a>
## 1.1.80 — 2026-09-16

One Export window for sound files, ADM and DDP; timecode fields you can type into; and a recording fix — the track's input list was empty until you armed a track.

### Recording: please try again

- **Fixed: the track header's "In" box showed no inputs**, whatever interface
  was connected, unless you had already armed a track or opened Audio I/O
  Settings. soundBlade opens the audio device for playback only at launch, so
  macOS is not asked for microphone access by an app that may never record —
  but the In box did not ask for the inputs before listing them. It does now.
- macOS asks for microphone access the first time the inputs are opened. It
  must be allowed. If it was refused earlier, turn it back on in System
  Settings > Privacy & Security > Microphone.
- **A take now warns you if the disk could not keep up**, instead of quietly
  writing a file with gaps in it.

### Export…

- **Export Sound File is now "Export…"**, with a **Format** choice: Sound File
  (BWF), **ADM** (BW64 master) or **DDP** (CD). Export ADM and Export DDP
  Image open the same window on their own format.
- **"Round to"** replaces the old CD Frames tickbox: tick it and choose a rate
  — 75 (CD), 24, 23.976, 25, 29.97 or 30. It works with or without Create
  Tracks from Marks; on its own it rounds the export's own start and end.
- A boundary two songs share rounds to the **same frame for both**, so there
  is no gap and no overlap between delivered files.
- **Several ADMs:** an EDL holding more than one master writes one file per
  song. If any song has been edited, **nothing is written** and the message
  lists every song that needs attention — a partial album that looks finished
  is worse than none.

### Fixed

- **Create Tracks from Marks wrote nothing at all** when no time selection was
  up. Every song was being clipped against an empty range.
- **Export ADM measured loudness over the whole EDL** instead of the song, so
  an album's songs were all stamped with the same wrong figure.
- **File > Open Recent** drops entries whose file has been deleted or renamed.
  Entries on a drive that simply is not mounted are kept.

### Editing and windows

- **Timecode fields format as you type.** Type digits and the separators
  appear; click a single field (just the seconds, say) and type over it. In
  the EDL header (L, R, In, Out, current time), Mark Info and Move In/Out.
- **Show Desk** is in the Windows menu, on **Cmd-1**.
- **Opt-P toggles** a track's plug-in panel — it closes it again if it is open.
- **Desk Events show their start and end times while you drag or resize them**,
  only while the mouse is down.
- Application Settings no longer has a **Fades** tab. Edit Fade Mode's Fade
  Library owns default fades.

### For testers: Tools > Run Test Suite

- The report and the file it saves now carry the **version**, so a report says
  which build produced it.
- **Details…** explains what to put in a fixtures folder and what each kind of
  test EDL is checked for.
- **Save and reopen:** every fixture EDL is saved, reopened and compared field
  by field, so anything an EDL fails to save back is named exactly.
- **Export checks:** an ADM master is copied and verified bit-identical to the
  original, a DDP is written and read back against the marks, and the Create
  Tracks from Marks and Round to rules are checked directly.

---

### Known limitations

- Recording beyond the input fix is still unverified — in particular the
  latency figure has never been checked against a physical loopback. If you
  have an interface, patch an output back to an input, record a click, and
  tell us whether it lands where it was played.
- The Export window's ADM format copies untouched masters only; an edited
  master still cannot be written, because that needs the streaming render.
- Exports still hold the whole render in memory, and Artist Connection clips
  are not included in exports.
- Test Suite fixture tests report that a render changed, not what changed in
  the edit.

[Back to the list of versions](#versions)

---

<a name="v1-1-79"></a>
## 1.1.79 — 2026-09-15

A built-in Test Suite, playback that follows the Source Layout, exact plug-in latency compensation, and a warning light when playback falls behind.

### For testers: Tools > Run Test Suite

- **Tools > Run Test Suite…** checks the app from the inside and writes a
  report. It never touches anything open in your Project.
- **Run All Tests** checks editing rules, recording (no interface needed),
  and plug-in latency on playback.
- **Your own test EDLs:** click **Choose Fixtures Folder…** and pick a folder
  holding a few EDLs you want checked, each in its own subfolder with its
  audio. Don't point it at your working Projects. The first run records a
  baseline beside each EDL; every later run compares against it and reports
  any difference.
- After a deliberate change to a test EDL, tick **Accept new baselines** once.
- **Save Report…** and send us the file, with any FAIL lines.

### Playback follows the Source Layout

- Tracks, objects, the Desk and its plug-ins, the meters and loudness now
  work in the **Source Layout**. The **Monitor Layout** is only what you
  listen through.
- The Object Panner, Object View, routing menu and Layout pane use the Source
  Layout's speakers, so a 7.1.4 mix on a stereo laptop is still panned in
  7.1.4.
- When Source and Monitor differ, the Monitor button turns amber; hover
  either for the pair.
- An EDL opened on a device with fewer outputs **keeps its saved Monitor
  Layout** — it no longer loses it when saved.
- The Preview window works the same way.

### Plug-in latency

- **Every plug-in lands in time**, including group plug-ins and a slot holding
  plug-ins with different latencies.
- **Mute all plug-ins** no longer moves the track (or its Edit Group) out of
  time.

### Desk

- A collapsible **Monitor** meter row below the Source meters shows what
  reaches the speakers.
- **LOCK flashes red** when playback falls behind — audio could not be read
  or processed in time. Please tell us when you see it, and what you were
  doing.

### Exports

- Plug-ins are printed at the rate the export actually renders at.
- Batch and album exports print each EDL's own plug-in settings.

### Also

- The Speaker Layout dialog shows the layout actually playing on this device.
- Playback no longer has a short gap after an edit while playing.

---

### Known limitations

- None of this has been run by testers yet.
- Fixture EDL tests only report that a render changed, not what changed in
  the edit.
- Close the Test Suite window before quitting the app while it runs.
- Exports still hold the whole render in memory, and Artist Connection clips
  are not included in exports.

[Back to the list of versions](#versions)

---

<a name="v1-1-78"></a>
## 1.1.78 — 2026-09-14

ADM masters carry their title, album and ISRC in and out, ADMs can cross-fade on an album, and filename tags are now one list for the whole app.

### ADM masters

- **Export ADM writes the release tags.** The title, artist and ISRC come from
  the song's Start mark; the album — and the artist, when the mark has none —
  from Mark Info. A field left empty keeps whatever the master already had. If
  there is more than one Start mark inside the master, you are asked first.
- **Opening an ADM reads them.** Each clip is named with the file's title, and
  the song gets a **Start mark** carrying its title, artist and ISRC. Default
  names Dolby tools fill in ("Atmos_…") are ignored.
- **End marks:** one at the end of the album, and one between songs only where
  they are AutoSpaced. Butt-spliced songs run to the next Start mark.

### Assemble Album

- **Cross-fade now really overlaps the ADMs**, so an album can be printed with
  its cross-fades.

### Edit menu

- **Convert Cross-fades to Butt Splices** — every cross-fade in the time
  selection (or on the selected clips) becomes a butt splice at its edit
  point. **Nothing moves and the fade lengths do not change**; the clips are
  trimmed back to their edit points, so the songs meet with no gap. A song's
  Start mark moves to the edit point with it.
- **Create CrossFade** no longer has "…" after it — it opens no dialog.

### Export Sound File

- **Wider**, with **Create Tracks from Marks** (was "Split at Marks"), Add Track
  Number and CD Frame on one row.
- **Tooltips on every control.**
- **Name tags are one list for the whole app.** Add and delete your own tags in
  **Application Settings > Name Tags**; they appear in Export Sound File and
  New Soundfile Settings straight away. The two custom tags you had are carried
  into the list, without duplicates. When there are more tags than fit, the
  rows wrap.

### Also

- **Hover a field whose text is cut off** to read all of it. Hover its left
  edge — or any field whose text fits — for its tooltip. Now also in Export
  Sound File, New Soundfile Settings and Application Settings.
- Mark Tab: **PQ List** is now **Open Log File**.

---

### Known limitations

- None of this has been run by testers yet.
- Exporting several ADMs at once — as separate files or as one album-length
  ADM — is not built yet. Export ADM still takes one master at a time.
- Undo after Convert Cross-fades to Butt Splices puts the clips back but not
  the Start mark it moved, and the command is not repeated in Edit-Locked EDLs.
- Text drawn inside list rows does not show its full text on hover.
- Rendering a 122-object master is slow — around 0.1× real time.

[Back to the list of versions](#versions)

---

<a name="v1-1-77"></a>
## 1.1.77 — 2026-09-14

Assemble Album builds one EDL and renders only what you tick, the Preview shows each channel's peak and an overview, and the Object View turns in 3D.

### Assemble Album

- **All the ADMs go into ONE EDL**, in the order chosen, with as many tracks as
  the widest one. Each ADM starts after the one before, meeting the way you
  choose — Butt Splice, Cross-fade or AutoSpace. You are asked every time
  unless "Do not ask again" is ticked.
- **Only ticked layouts are rendered.** With no Album Renders layout ticked
  nothing is rendered and no layout dialog appears — the ADMs just open.
- **Renders open as separate tracks** in the Album View — one track per
  channel, named for its speaker, all in one Edit Group.
- **Featured tracks carry over** from the Preview, and an EDL with featured
  tracks shows them instead of being collapsed.
- **It always opens in a new, empty Project.**
- While an album renders, **only the EDL being rendered is locked**; the others
  stay editable.

### Preview

- **Peak and Overview columns** for every channel, from a fast scan that starts
  as soon as a file is selected. Peak is in dBFS (red at full scale); Overview
  shows where there is audio. When the scan finishes, the EDL's waveforms are
  built in the background, so opening the file later is quicker.
- **Columns:** … M, S, F, Skip, Peak, Level, Overview. Skip is narrower and
  drawn like M and S, with a red X when on. The window is wider so every column
  fits without scrolling sideways.
- **Open EDL** (was "Open Into EDL") adds each file as its own EDL at the bottom
  of the open Project, or into a new empty Project when none is open.
- **Assemble Album** (was "Open Into Album View").
- **Every tickbox starts empty** — nothing is ticked for you.
- **Start time** shows as timecode with frames, and Open EDL places the file at
  that time.
- **Bed configuration** tells 7.1 from 5.1.2 on an ADM, from its speaker labels.
- **Fixed:** clicking the time to type a new one closed straight away.

### Object View

- **Drag to turn the room in 3D**; double-click, or press Room, Front, Side or
  Top, to put it back.
- The room is drawn larger, and the window keeps a square view so the room never
  resizes as it turns.
- **Show Mute** (off by default) shows or hides muted tracks. The other
  checkboxes are now **Names** and **Speakers**.

### Also

- The **F (Featured) column** follows changes made anywhere, as M and S do.
- Importing a large ADM no longer freezes the window when the import finishes.

---

### Known limitations

- None of this has been run by testers yet.
- The Album View always shows all its channels; Featured applies to the
  programme EDL.
- A file placed at its start time (e.g. 01:00:00) sits that far into its EDL.
- Show Mute is not remembered between sessions.
- Rendering a 122-object master is slow — around 0.1× real time.

[Back to the list of versions](#versions)

---

<a name="v1-1-76"></a>
## 1.1.76 — 2026-09-13

PQ List now makes a proper album log sheet as a PDF, and Mark Info holds the album's Title and Artist instead of DDP controls.

### PQ List makes an album Log Sheet (PDF)

- **The PQ List button in Mark Info now saves a formatted PDF log sheet**
  instead of the old plain-text PQ Log. It opens as soon as it is saved.
- The sheet shows:
  - your **logo** (optional), **Mastered by**, **studio name**, **address** and
    **website / phone**;
  - the **date**, **session** (the EDL's file name), **number of titles** and
    **disc duration**;
  - the album's **Title** and **Artist**;
  - a table — **# / TITLE / START / DURATION / ISRC** — with each track's Title
    and Artist beneath it, and a **Total Duration**. The heading repeats on
    every page, and pages are numbered.
- Times read like **1 h 9 mn 3 s 320 ms**, measured from the start of track 1.
- A track's Artist is its own Artist from Mark Info, or the album's Artist when
  the track has none.
- **Studio details are asked for when you press PQ List** and remembered for
  every album after that. **Choose Logo…** picks a PNG or JPEG.
- TrackList and ExportList are unchanged.

### Mark Info

- **New Album and Artist fields** at the top, saved with the EDL. They go on
  the log sheet.
- **Execute, Path and Status are gone** — Mark Info is not where DDPs are
  made. Use **File ▸ Export ▸ DDP Image**.
- TrackList and ExportList show the saved file in the Finder when done.

---

### Known limitations

- The log sheet is A4.
- ADM tag writing has not been run on real masters yet — copies only, please.
- CSV import into Mark Info, and DDEX import/export, are planned.
- Rendering a 122-object master is slow — around 0.1× real time.

[Back to the list of versions](#versions)

---

<a name="v1-1-75"></a>
## 1.1.75 — 2026-09-13

Titles and album go into ADM masters, metadata comes in from a CSV, PCM masters open as separate tracks, and the video commands move to where you would look for them.

### ADM masters carry their titles

- **The metadata window now writes Track Name, Artist, Album, Genre and ISRC
  into an ADM master**, instead of refusing. They follow the standards:
  - **Track Name** becomes the ADM programme name (`audioProgrammeName` —
    what Atmos tools show; the masters we checked say "Atmos_Master").
  - All five also go in as **EBU Core** entries beside the ADM (ITU-R BS.2076 /
    EBU Tech 3293), not inside it — the ADM itself is left byte for byte.
- Opening the window on an ADM master now shows those fields from the file.
- **Export ADM keeps them** — it passes the rest of the metadata through.
- **Please try this on COPIES of masters first**, and check a saved copy still
  opens in the Dolby Atmos Renderer. The metadata grows, so the end of the
  file (after the audio) is rewritten; the audio itself never moves.

### Import metadata from a CSV

- **Import CSV…** in the metadata window fills the fields from a spreadsheet,
  for you to check before pressing Save. Two shapes work:
  - a **header row naming the tags** — plain ("Title", "Artist", "ISRC") or
    store-style ("TRACK | Title (*)", "ALBUM | Title (*)", "TRACK | ISRC Code");
  - **one column of ISRCs with no header**.
- The row for the file is found from its ISRC, or the track number at the start
  of its file name; otherwise you choose from a list.

### Preview

- **A PCM master always opens as separate tracks**, one per channel, whether or
  not any channels were skipped — the same as an ADM, so Featured, Mute, Solo
  and Edit Groups work per channel. (It used to open as one track carrying
  every channel when nothing was skipped.)
- **The Video… button is gone.** Use **Windows ▸ Video Window** with the
  Preview window in front — it shows the Preview's own picture.

### Video menus

- **File ▸ Open Video…** — chooses the video for the selected EDL (it was
  View ▸ Set Video File…).
- **Windows ▸ Video Window** (⌘8) — shows or hides the video window.

---

### Known limitations

- ADM tag writing is new and has not been run on real masters yet — copies
  only, please.
- A master the Preview had not finished reading still opens as one track.
- CSV import fills one file at a time; filling a whole album in Mark Info, and
  DDEX import/export, are planned.
- Rendering a 122-object master is slow — around 0.1× real time.

[Back to the list of versions](#versions)

---

<a name="v1-1-74"></a>
## 1.1.74 — 2026-09-13

Choose which tracks you want to see — in the Preview before a master is opened, and in an EDL's Layout — and a fix for a crash on quit.

### Featured tracks

- **An "F" (Featured) column** beside M and S, in the **Preview window's**
  track list and in an EDL's **Layout** tab. Click to feature a track; click
  inside a selection for the whole selection; Option-click for the whole Edit
  Group. It lights green when on.
- **In the Preview**, the ticks are remembered per file (like Skip). **Open
  Into EDL** and adding a master to an existing **Album View** carry them
  across: the EDL opens with those tracks featured and showing Featured tracks
  only. With nothing ticked it opens showing every track, as before.
- **In the Layout tab**, ticking F updates the EDL straight away, and is saved
  with it. If the EDL is showing Featured tracks only, the view follows as you
  tick; unticking the last one shows every track rather than none.

### Fixes

- **Crash on quit.** Quitting — especially while waveforms were still being
  built — could crash as the app closed. The background waveform scanner is
  now shut down while the app is still quitting normally, instead of in the
  last moments of the process.

---

### Known limitations

- A plain multichannel (PCM) master with nothing skipped opens as ONE track
  carrying every channel, so there are no separate tracks to feature.
- A master the Preview had not finished reading — and a brand-new album made
  with Open Into Album View — is read again from the file, and does not carry
  Featured ticks yet.
- Window layouts are kept on this computer, keyed by the Project's file.
- Rendering a 122-object master is slow — around 0.1× real time.
- ADM export does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-73"></a>
## 1.1.73 — 2026-09-13

Albums ask how programmes meet and cross-fade for real, Projects remember their windows, the Object View reads better, and the Desk explains itself.

### Album View

- **You are asked how programmes meet: AutoSpace, Butt Splice or Cross-fade.**
  Assemble Album asks with the layouts; Open Into Album View from the Preview
  asks every time — for a new album and when adding to an existing one. The
  menu opens on your last answer, so OK repeats it.
- **Cross-fade now actually cross-fades.** Each programme overlaps the one
  before it and both sides get your **Default CrossFade** (durations, curves
  and Overlap %). It used to come out as a butt splice.
- **"Do not ask again"** on both album dialogs uses your last answers without
  asking. Turn the question back on in **Application Settings ▸ Editing Tools
  ▸ Ask for Edit Insert Options**. (Assemble Album still asks if no layouts
  have ever been chosen.)
- Each programme's own EDL lines up with where its programme actually landed
  on the album, cross-fade included.

### Projects remember their windows

- **Every window comes back open, where it was, when you reopen a Project**:
  Files/Marks/Layout, Video, New Soundfile Settings, and for each EDL its Desk,
  Loudness Meter, Object Panner and Object View. A window that was closed stays
  closed. Remembered when you save, close the Project window or quit — closing
  without saving still remembers the windows.
- Fixed: the Object View did not reopen at launch and forgot its position on
  quit.
- Not yet: plug-in editor windows, and the Preview window.

### Object View

- **The room fills the window.** The space below ear level — almost always
  empty in an Atmos mix — is squeezed so the floor sits just under ear level,
  and the window keeps the room's shape as you resize it.
- **Stacked objects show a count.** Objects on the same spot get a small badge
  ("4"); hover to list every object in the stack.
- **Edit Group colours show.** Each object is filled with its group colour and
  ringed with it, with a solid dark rim so overlapping objects separate. It was
  decided per object but never drawn once the dots became meters.

### Desk

- **Tooltips** on SR (the EDL's sample rate), LOCK (what a locked sample rate
  means), DITHER (the monitoring dither mode and what a click does) and each
  plug-in slot (how a plug-in is opened across the bus, and how narrower ones
  are copied).

### EDL menu

- **Move Selected EDL Up / Down / to Top.** "to Top" is new; moving an EDL now
  marks the Project as changed.

---

### Known limitations

- **None of this has been run by testers yet** — especially Cross-fade album
  assembly and window restore on a Project with several EDLs.
- Window layouts are kept on this computer, keyed by the Project's file, not
  inside the Project file.
- The Preview window's object room keeps its fixed column.
- Rendering a 122-object master is slow — around 0.1× real time.
- ADM export does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-72"></a>
## 1.1.72 — 2026-09-12

Edit Fade Mode's Prev and Next now step through every edit on the track.

### Edit Fade Mode

- **Prev and Next go to every edit on the track, not only fades that have a
  length.** They used to skip butt splices, gaps and any edit without a fade,
  so on a typical track Next stopped working after the last crossfade. Now,
  in timeline order:
  - the **first clip's start** is a fade-in;
  - a **crossfade or butt splice** between neighbouring clips opens as a
    crossfade;
  - a **gap** between neighbouring clips opens as a pair — the fade-out, the
    silence and the fade-in together;
  - the **last clip's end** is a fade-out.

  So Prev is greyed only on the first fade-in of the track, and Next only on
  the last fade-out.

- **An edit with no fade yet opens properly.** Its fields read 0; give it a
  Duration to make a fade. Auto Zoom shows 1.5 seconds around the edit instead
  of a tiny sliver, and Play and Nudge Auto Audition play a second either side
  of the edit instead of nothing.

---

### Known limitations

- **Please test Prev/Next across a whole track** — crossfades, butt splices,
  gaps, and the first and last clip.
- The Edit Fade Mode changes in 1.1.71 (Edit Groups, Lock Sound, Ripple Until
  Black, Align Fades, selections) are still to be confirmed on real sessions.
- Lock Sound starts unticked each time EFM opens.
- Prev/Next only step between edits on the same track.
- Rendering a 122-object master is slow — around 0.1× real time.
- ADM export does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-71"></a>
## 1.1.71 — 2026-09-12

Edit Fade Mode brought in line with the soundBlade manual (4.2): selections, Lock Sound, Ripple Until Black, Align Fades and Audition Both now behave as documented, and an edit in EFM carries across every track in the Edit Group.

### Edit Fade Mode

#### Edit Groups
- **An EFM edit now applies to every track in the Edit Group, as you make it.**
  Trims, edit-event moves, slips, fade settings and the audition Solo/Mute all
  follow onto the matching clip of each group track live — the way a fade
  dragged on the timeline already did. Before, only the fade settings were
  copied, and only on OK, so a group track kept its old clip positions.
  Ripples move the later clips on every group track too. Cancel puts every
  group track back. Clip gain is not copied.

#### Selections (manual 4.2.1)
- **Clicking in the In or Out Fade Panel sets the Edit Point**, shown as a
  light-blue line in the panels; the playhead follows when stopped. A click
  no longer moves the fade — drag the fade's edit-event handle for that.
- **`]` moves the Out fade, `[` the In fade, to the Edit Point** (to the
  playhead when there is no Edit Point).
- **Clearing the In or Out check box auditions the other side alone.** Its
  **S** button lights to show it. Tick both again to hear both.

#### Global modes (manual 4.2.3)
- **Lock Sound off** — moving the edit event slips the In fade's sound with it,
  along with the sound after it. Moving the **Out** edit event on a crossfade
  now carries the In clip too; it used to be left behind. Moving the **In**
  side moves the whole In clip; it used to trim it and leave a gap or overlap
  after it.
- **Lock Sound on** — the In sound stays locked to the timeline; the edit
  trims or extends the In clip's front, so you can open a gap or overlap the
  fades. Nothing after it moves.
- **Ripple Until Black on** — only the In fade's segment and the segments
  butted up against it move; the ripple stops at the first silence. The clip
  straight after a gap used to move anyway.
- **Align Fades on** — an Overlap change applies reciprocally to the other
  side, keeping the crossfade aligned. **Off** — both sides take the same
  Overlap and move in opposite directions. Align Fades used to have no effect
  whenever both sides were enabled.

#### Audition (manual 4.2.4)
- **Audition Both plays both fades whatever Solo is set to.** Turning it on
  clears any Solo, and Play and nudge audition clear it again before playing.
  Clicking the Out or In row to pick one half turns Audition Both off.
- Nudge Auto Audition plays the fade after every nudge (unchanged).

#### Fade Library
- **Save Fade shows a menu of the five Default names and a name field.**
  Pick a Default to replace it, or type a name for your own fade — a typed
  name wins when both are set.

---

### Known limitations

- **None of the Edit Fade Mode changes above have been run yet.** Please test
  on copies of real sessions, especially: an EFM edit on one track of an Edit
  Group, Lock Sound on/off with Ripple Until Black on/off, and Align Fades.
- EFM matches each group track's clip when it opens, by start time (within
  0.05 s). A group track whose clip does not line up will not follow.
- Lock Sound starts unticked each time EFM opens.
- Prev/Next only step between fades on the same track.
- The metadata window's Save (1.1.69) is still new — try it on copies first.
- Rendering a 122-object master is slow — around 0.1× real time.
- ADM export does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-70"></a>
## 1.1.70 — 2026-09-12

Edit Fade Mode plays one half of a crossfade, opens both fades across a gap, and keeps the fade in place while you zoom. Export gains Genre and tells you when an ISRC was left out.

### Edit Fade Mode

- **Choose which half Play plays.** Click the **Out** row (or its header) and
  Play plays only the outgoing side; click **In** for only the incoming side;
  click the **Result** row for the whole crossfade. The **S** (Solo) button
  lights on the side you will hear. Clicking a row's header selects it without
  moving the edit point — a click in the waveform still moves it.

  These are the same audition Solo/Mute buttons as before: you can still click
  them directly, and OK or Cancel puts every clip's real mute state back.

- **An end fade and a start fade with a gap between them open together.**
  Select both clips and open Edit Fade: EFM shows the Out and In rows, and the
  Result row shows both fades with the silence between. Each fade is edited
  on its own — nothing overlaps, so Overlap, Align Fades, Edit Pt Offset and
  linked Duration do not apply and are hidden. Only **selected** clips on the
  same track are paired; a real crossfade still opens as a crossfade.

- **The fade is centred when EFM opens.** The target is the edit point, or the
  middle of the gap for a pair, with every fade involved in view.

- **Zooming keeps the fade where it is.** While EFM is open, zooming in or out
  — Up/Down, Cmd +/−, the mouse wheel, Option-drag, previous/next zoom level,
  or a Zoom Lock from another EDL — holds the fade at the same place on screen:
  centred stays centred, and off to one side stays there. Dragging the overview
  bar still sets the view directly.

### Export

- **Genre.** A Genre box beside Album — choose from the list or type your own.
  Written to every file (RIFF INFO `IGNR`) and remembered for next time. The
  metadata window uses the same list.
- **You are told when an ISRC was left out.** A code that is not 12 letters or
  digits cannot be written into the file. It used to be dropped silently; now,
  once the export finishes, a message lists each file that went out without its
  ISRC and the code it had.

### ISRC

- **Auto-Increment only counts on from a code that is fully to spec.** A code
  with an error (red) or a warning (yellow) is kept as typed, but the next
  track is not filled from it.

---

### Known limitations

- **Please test Edit Fade Mode's new behaviour on real sessions** — none of it
  has been run yet. In particular: playing one half, a gap pair, and zooming
  with the fade off-centre.
- With **Auto Zoom** on (the default), the EFM waveform rows stay framed on the
  fade and do not follow the timeline's zoom; turn it off to have them follow.
- The metadata window's Save (1.1.69) is still new — try it on copies first.
- Tags are written as RIFF INFO only; ID3 is not written yet.
- Rendering a 122-object master is slow — around 0.1× real time.
- The Desk is still master-bus only.
- ADM export does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-69"></a>
## 1.1.69 — 2026-09-12

A new metadata window for files, marks that keep their order and follow Red Book spacing, a rearranged EDL header, and an About box.

### File metadata window

- **Show BWF Meta-Data…** (File Browser tab, and right-click a file or ADM in
  the Preview window) opens one window that shows a file's `bext`, its tags
  and its format facts, and lets you set them. Selecting a clip on a track
  shows the file underneath it.
- **Genre** — choose from the list or type your own.
- **Tags are written as RIFF `LIST/INFO`** (Track Name, Artist, Album, Genre) and the
  **ISRC into `axml`**, without rebuilding the file — every other chunk in it
  is left exactly as it was. Before, a save could silently lose the tags or
  drop chunks soundBlade did not recognise.
- **ADM masters are protected.** Tags and artwork are not written into a file
  that carries ADM (`axml` + `chna`), and the window says so. A `bext` is not
  added to an ADM master by default — see the manual's metadata section for
  why.
- **Export carries each mark's Artist** into the files it writes.

### ISRCs

- An ISRC must be **12 letters or digits** (hyphens and spaces are ignored).
  Anything else is an **error**, in red.
- A 12-character code that does not follow the standard shape
  (CC-XXX-YY-NNNNN — five letters or digits, then seven digits) is **accepted
  with a yellow warning** rather than called valid. Codes are supplied to you,
  so soundBlade flags them and does not change them.
- The metadata window shows this live as you type; the Mark Tab lamp and
  status line turn yellow when there are warnings but no errors.
- **Auto-Increment ISRC:** with it checked, typing an ISRC in the Mark Tab and
  pressing Return fills the next track with the code plus one and moves down.
  Return in the Name column still does what it did.

### Marks

- **Marks are always kept in time order** — the Marks menu, the Mark Tab and
  every report agree, and the menu now shows each mark's name.
- **Dragging a mark stops at its neighbours** and at Red Book CD spacing: a
  4-second minimum track, the Min Index Width, and never two marks on one CD
  frame. A small bubble says which rule stopped it.
- **Typing a Start time in the Mark Tab can move a mark past others**; the
  list reorders, and any rule it breaks is shown in the status area.
- **Mark Info…** is the first item in the Marks menu and opens the Mark Tab.

### EDL header

- The zoom buttons sit to the right of the monitor layout button.
- A **Layout** button above the Source Layout button opens the Layout tab.
- **With no source layout the button reads "Source" in grey** instead of
  "Off". The menu still calls the choice Off.
- SRPs and Marks sit to the right of Edit Lock; Edit Lock is above Zoom Lock;
  Tracks and Sample Rate have swapped places.

### Also

- **About soundBlade** in the soundBlade menu, with or without a Project open.
- **New windows open centred and staggered** on the screen you are working on,
  instead of piling up in the top-left corner — Desk, Loudness, Object Panner,
  plug-in panels, Video, metadata and more.
- **File menu with no Project open** shows every command, greying the ones
  that need a Project.
- **Artist Connection:** signing out warns if uploads are still running; an
  album's tracks appear as they arrive instead of all at the end; one sign-in
  is shared by every Project window.
- **New ADM Master** has been removed from the EDL menu for now. Open an ADM
  authored elsewhere (Pro Tools and others) and edit it instead.

### Fixes

- **A crash when editing a track name in the Mark Tab** and pressing Return.

---

### Known limitations

- **The metadata window's Save is new code** — please try it on copies first,
  and report any file another application no longer reads the same way.
- Tags are written as RIFF INFO only — **ID3 is not written yet**, and files
  whose tags live only in ID3 will show them empty.
- Setting metadata on a **set** of files, CSV import and reading from another
  file are planned, not built.
- Export **drops an ISRC that is not 12 characters** without saying so.
- Track 1's 2-second pregap is not enforced on drag.
- Rendering a 122-object master is slow — around 0.1× real time.
- The Desk is still master-bus only.
- ADM export does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-68"></a>
## 1.1.68 — 2026-09-12

Edit Fade Mode gets its menu back, the Fade Library gets its Defaults, and four things that quietly did nothing now do something.

### Edit Fade Mode

- **Prev and Next actually step through the fades on the track.** They walked
  the clips in the order they happened to be stored in rather than the order
  they sit on the timeline — and since making a crossfade *splits* a clip,
  which puts the new half at the end of that list, the two orders came apart
  the moment you made one. The buttons wandered off into unrelated clips,
  found no fade, and did nothing at all.

  They now move between fades in **time order**, and a crossfade counts as one
  fade rather than two edges, so Next goes to the next crossfade and not to
  the other half of the one you are on. When there is no fade that way, the
  button is greyed rather than dead.

- **Stepping keeps your edit.** Prev/Next used to throw away whatever you had
  just changed about the current fade. Each fade you step through is now
  committed as its own undo step, so you can work along a run of fades and
  keep all of it.

- **There is an EFM menu again**, in the menu bar, present only while Edit Fade
  Mode is open and belonging to the EDL in front. It holds:

  - **Fade Library** — the five Defaults and your nine saved fades, plus
    **Save Custom Fade as…** and **Delete Saved Fade**
  - **Select Fade Type** — Linear / Cosine / Exponential, per side, ticked on
    the one in force
  - **Select Parameter Field** — which field the Parameter slider drives
  - **Select Next Fade** / **Select Previous Fade**
  - **Nudge Left / Right A, B and C**, each showing its own amount

  Everything in it does exactly what the panel's own controls do — they are
  the same actions, not a second implementation.

---

### The Fade Library

- **The five Default Fades are in the library**, listed above your own saved
  fades: `DefaultInFade`, `DefaultOutFade`, `DefaultCrossFade`,
  `DefaultCrossFadeOut` and `DefaultCrossFadeIn`.

- **Save Custom Fade as… asks for a name, not a slot.** Type one of those five
  names and you set that Default; type anything else and it goes into the slot
  already carrying that name, or the first free one. This is how the manual
  describes it (4.2.9), and it is the only way to say "save this as the
  default" — picking a slot first could not express it.

  The name is matched without regard to capitals, so `defaultcrossfade` works.
  A full library says so rather than failing quietly.

- **Delete Saved Fade** removes one of your saved fades. The slot numbers stay
  where they are, so nothing below renumbers and Option+1…9 keeps meaning what
  it meant.

- **Default Fades are now global.** They used to be stored inside each EDL, so
  the same "Save Fade as Default" gesture produced different results depending
  on which EDL was in front, and a default set in one EDL was invisible in the
  next. There is now one set for the whole application, saved with your other
  preferences.

  **Please note: defaults you had set inside an existing EDL do not carry
  over.** They start at the factory values — Fade-In and Fade-Out 0.0,
  CrossFade 0.01 at 50% overlap, all Cosine. Set them once from a fade's
  right-click menu, or from the Fade Library, and they stick everywhere from
  then on.

  Application Settings ▸ Fades resets the one shared set, and now works with
  no EDL open.

---

### Fixes

- **Open Recent did nothing.** Once a Project window was open, every entry
  under File ▸ Open Recent — Projects, EDLs and media alike — was inert. The
  menu showed the right things and selecting one had no effect and no error.
  Fixed. (Open Recent *before* any window was open was unaffected, which is
  why it looked intermittent.)

- **Save dialogs no longer lose everything after a dot.** Typing `Mix.1` into
  Save EDL As, Save Project, Export EDL, Export Selection or Export to Reaper
  dropped the `.1` — and for a Project it named the project folder `Mix`. All
  five now keep the whole name. (The EDL name field was fixed in 1.1.67; this
  is the rest of them.)

  One change worth knowing: at the two export-to-WAV dialogs, typing a
  different extension such as `Mix.aiff` now gives you `Mix.aiff.wav`. The
  file was always a WAV; the name now says so.

- **The Export dialog's Bit Depth starts at the right resolution.** It always
  opened on 24, whatever the EDL was made of, so a 32-bit float master opened
  at 24 and a 24-bit master could be exported at 16 with nothing on screen to
  warn you. It now reads the EDL's own files and opens on the **highest**
  depth it finds — never lower. You can still choose anything you like.

- **The Bit Depth name tag follows the box.** Changing the depth did not
  update the `<bit depth>` tag in the export filename.

---

### Known limitations

- **Everything above is untested in a running app** — it compiles, and the
  behaviour is reasoned rather than observed. Edit Fade Mode in particular
  deserves a real session: the menu appearing and disappearing, stepping
  through a run of crossfades, and saving a fade as `DefaultCrossFade` and
  watching a new clip pick it up.
- Two items from the legacy EFM menu are **not** built — the ones around
  "Select … Edit Point Field" and "Offset". They were not legible enough in
  the reference screenshot to reproduce faithfully.
- **Edit Lock (1.1.66) is still new.** It has been built against the aligned
  stereo / 5.1 / ADM case it was designed for; please report anything that
  propagates to the wrong place, and check the alignment warning is telling you
  the truth.
- **Rendering a 122-object master is slow** — around 0.1× real time. It runs in
  the background, so the app stays usable; the speed itself is not addressed.
- **Recording** has been used for real takes but not across many interfaces,
  sample rates and channel counts.
- No audible input monitoring; armed tracks meter their input but do not pass it.
- Latency compensation covers the computed digital path only.
- The **Desk** is still master-bus only; per-track strips are designed, not built.
- The Preview does not yet carry track names, edit groups or mute/solo across
  when you open a master — only Skip and the layouts.
- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-67"></a>
## 1.1.67 — 2026-09-12

A tighter EDL header, Stop that returns to where you started, and the Edit Target spelled out on every track.

### The EDL header

- **The timecode read-outs are regrouped into two columns.** The selection is
  on the **left** — L, its length, R — and the Edit Points are on the **right**
  — In, its length, Out. Each pair now sits with its own duration between its
  two ends, instead of the two lengths sharing the middle column while the
  points they measured sat on opposite sides of the current time. Current Time
  has the centre to itself.

- **The header is shorter.** The timecode background comes down from 70 to 50
  pixels and the header itself loses another 10, handed back to the tracks. No
  text got smaller — the rows were carrying padding the digits never needed.

- **The logo is 24px**, sized for the header it is actually in.

The master volume fader is deliberately unchanged. It sits beside the timecode
and was sized from it, so it would have quietly lost 20 pixels with it; a fader
is sized by being usable, not by the read-out next to it.

---

### Editing

- **Stop returns the playhead to where Play started.** Play from an edit point,
  stop, and you are back at that edit point ready to listen again — rather than
  wherever the music happened to reach.

  If you have **Edit Point to Playhead** switched on for an EDL, that still
  wins there. The two are exact opposites — one moves the Edit Point to the
  playhead, the other moves the playhead back to the Edit Point — so the
  setting you asked for explicitly is the one that applies.

  Stop on an already-stopped transport does nothing, and scrubbing still leaves
  the playhead under the mouse.

- **Ctrl-click the Edit Group bar for the Edit Group menu.** One click to open,
  one click to set — no right-click and no submenu. Holding a letter and
  clicking the bar still works and is still faster once you know the letters.
  Acts on the whole selection when the track is part of it.

- **Source and Destination are spelled out on the track.** A new button under
  the Input field, in the O button's column, showing **S** on blue for Source,
  **D** on yellow for Destination, and grey when neither. Clicking it cycles
  None → Source → Destination. Ctrl+S / Ctrl+D / Ctrl+N are unchanged.

  It appears at **Small** track height and above; below that there is no row to
  put it in. The colours are the same ones the Edit Group bar, the EDL border
  and the selected-group border already use — they all read one definition, so
  they cannot disagree with each other.

---

### Fixed

- **An EDL name no longer loses anything after a dot.** Typing `Mix.1` left you
  with `Mix`. The name was being written through a call that treats the last
  dot as the start of a file extension and replaces it, so version-style names
  were the exact case that broke. Names like `Mix.1` and `Take.2.final` are
  kept whole.

  Note this is fixed for the **EDL name field**. Typing a dotted name into a
  *save dialog* can still lose the same way; that is a separate path and is
  not addressed here.

---

### Known limitations

- **Edit Lock (1.1.66) is still new.** It has been built against the aligned
  stereo / 5.1 / ADM case it was designed for; please report anything that
  propagates to the wrong place, and check the alignment warning is telling you
  the truth.
- **Rendering a 122-object master is slow** — around 0.1× real time. It runs in
  the background, so the app stays usable; the speed itself is not addressed.
- **Recording** has been used for real takes but not across many interfaces,
  sample rates and channel counts.
- No audible input monitoring; armed tracks meter their input but do not pass it.
- Latency compensation covers the computed digital path only.
- The **Desk** is still master-bus only; per-track strips are designed, not built.
- The Preview does not yet carry track names, edit groups or mute/solo across
  when you open a master — only Skip and the layouts.
- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-66"></a>
## 1.1.66 — 2026-09-10

**Edit Lock** — cut a programme across all of its deliverables at once — plus a run of editing and interface fixes.

### Edit Lock

You often have the same programme laid out as several deliverables: a stereo
master, a 5.1, the ADM. They are aligned to the same timeline, and an edit that
lands in one has to land in all of them.

**Turn Edit Lock on in each EDL that should follow.** A geometry edit made in
any of them is repeated in the others.

- **It matches by Edit Group.** An edit in group A is repeated on group A
  elsewhere. An EDL that has no group A is left alone — a stereo fold with
  nothing at group C is not a failure, it simply has nothing there to cut.
- **It travels as boundaries, not clips.** Locked EDLs hold different material,
  so what is copied is *where the edit is* — a cut at 3:12.400 is a cut at
  3:12.400 everywhere.
- **It warns if the EDLs are not aligned.** Because position is the shared
  identity, an EDL starting somewhere else would take every edit in the wrong
  place. Locking one that does not line up asks first, and you can cancel.
- **Undo works across all of them.** Each EDL keeps its own step and Undo
  applies to every locked EDL together.

**What propagates:** split (Create CrossFade), delete, trim either edge, move,
fade duration and curve, and delete cross-fade.

**What does not:** gain, mute, solo, polarity, plug-ins, speaker layout and
naming. Those describe one deliverable, and copying them between deliverables
would be wrong rather than merely surprising.

---

### Editing

- **Create CrossFade… is now in the lane menu over any clip**, not only inside
  a time selection, with its Ctrl-G shortcut shown. Over an existing cross-fade
  it appears **disabled** rather than vanishing — it genuinely cannot cut
  there, and a menu that changes shape depending on where you click reads as a
  missing command.

- **Track View — feature a whole Edit Group, or the Bed**, in one pick rather
  than ticking a dozen tracks. (Add Bed to Featured shipped in 1.1.65
  permanently greyed out: nothing in the app ever recorded which tracks were
  the bed. It does now.)

- **Fixed: the "New ADM Master" template renamed its own pre-named bed tracks.**
  The guard meant to protect L/R/C from being renamed had never worked, for the
  same reason.

---

### Interface

- **Hover any text that does not fit and see all of it** — paths, file names,
  anywhere. Only when it is actually truncated.

- **The Desk Window now matches the Preview's Desk**, and the **master volume**
  is the same blue in both. One colour definition drives every surface, so the
  two cannot drift apart again.

- **The EDL name sits above the SRPs / Marks / Tracks buttons** and is 190px
  wide — long enough to read a real name.

---

### Known limitations

- **Edit Lock is new.** It has been built against the aligned stereo / 5.1 /
  ADM case it was designed for; please report anything that propagates to the
  wrong place, and check the alignment warning is telling you the truth.
- **Rendering a 122-object master is slow** — around 0.1× real time. It runs in
  the background, so the app stays usable; the speed itself is not addressed.
- **Recording** has been used for real takes but not across many interfaces,
  sample rates and channel counts.
- No audible input monitoring; armed tracks meter their input but do not pass it.
- Latency compensation covers the computed digital path only.
- The **Desk** is still master-bus only; per-track strips are designed, not built.
- The Preview does not yet carry track names, edit groups or mute/solo across
  when you open a master — only Skip and the layouts.
- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-65"></a>
## 1.1.65 — 2026-09-10

No more privacy prompts at launch, long jobs run in the background, and the Preview window grows up: picture, measured loudness, and the album's own render settings.

### Privacy prompts at launch

- **soundBlade no longer asks for Music, network-volume or microphone access
  every time it starts.** The file browser is now built the first time you open
  it rather than at launch — building it scanned your Music folder and
  enumerated every mounted volume, whether or not you ever opened the panel.
  And the audio device now opens with **no inputs** until you actually need
  them: arming a track, or opening Audio I/O Settings. macOS asks in context,
  once, instead of at every launch.

---

### Things that used to make you wait

- **Assembling an album renders in the background.** The app stays usable while
  it prints — the EDLs being read are locked and marked, and everything else
  works. Progress and Cancel sit in a panel rather than a modal window.

- **Measure Loudness in the Preview runs in the background too.** The Measure
  button becomes its own Cancel, and the loudness pane shows progress. The file
  selection is locked while it runs, since the measurement is reading it.

- **Fixed: Cancel could hang and then kill a render by force.** A render only
  checked for cancellation between clips — and on a 122-object master a clip is
  the whole programme, so Cancel waited, timed out, and the thread was killed
  mid-write. It now stops within a fraction of a second.

---

### Preview

- **Picture, in its own window.** Set a movie for a master and it follows
  playback, with Space working from either window. Each master remembers its
  own movie, and the pairing survives a relaunch.

- **Measured loudness**, with **Reset** and **Measure…** — Measure renders the
  master at its own sample rate and measures it properly, which is what answers
  "what does this deliver at" without playing an hour of it.

- **The album's render layouts are set here**, as a column of tick boxes. It is
  the same set the Assemble Album dialog holds, so the two cannot disagree —
  and **Open Into Album View** no longer silently reuses a set you never chose.
  With nothing ticked, it asks.

- **Select several masters at once** and open them all — one EDL each, or all
  onto an album. Edit Metadata takes the first.

- **A plain multichannel master now plays correctly.** Every row carried the
  whole interleaved file, so a 7.1 master played as eight overlapping copies of
  itself. Each row is one channel now, which also makes per-row Mute, Solo and
  **Skip** mean what they say.

- **Skip is honoured when you open.** A master with channels skipped opens as
  one track per kept channel — a single track carrying an interleaved file *is*
  every channel in it, so there was no other way. Nothing skipped still opens as
  one track. This matters for delivery: an ADM carrying blank objects gets
  refused.

- The window is **1400 × 760** (minimum 1200 × 600), which leaves the Desk room
  for a 7.1.4 master's twelve channels alongside the new column.

---

### Track View

- **Feature a whole Edit Group, or the Bed**, in one pick rather than ticking a
  dozen tracks one at a time.

---

### Fixes

- **Fixed: a crash on quit and another on closing Audio I/O Settings.**
- **Fixed: the Preview's Layout list kept showing a file you had closed.**
- **Fixed: opening a plain PCM master created an EDL but put nothing in it.**
- **Fixed: a multichannel master was routed as if it were stereo** — its
  channels were numbered against whichever layout the previous file left behind.
- **Fixed: the loudness figures measured a 7.1 file as if it were stereo.**
- **Fixed: the playhead never moved during Preview playback**, and the sample
  rate never appeared. The rate now also turns **yellow** when the file is being
  sample-rate converted for monitoring.

---

### Known limitations

- **Rendering a 122-object master is slow** — around 0.1× real time. Backgrounding
  it makes the wait workable; the speed itself is not addressed in this release.
- **Recording** has been used for real takes but not across many interfaces,
  sample rates and channel counts.
- No audible input monitoring; armed tracks meter their input but do not pass it.
- Latency compensation covers the computed digital path only.
- The **Desk** is still master-bus only; per-track strips are designed, not built.
- The Preview does not yet carry track names, edit groups or mute/solo across
  when you open a master — only Skip and the layouts.
- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-64"></a>
## 1.1.64 — 2026-09-10

The **Preview** window becomes a window of its own — it no longer belongs to a Project — plus a crash fix on the audio thread and a run of Preview corrections.

### Preview

- **Renamed to Preview** (File > Import > Preview…, and now also in the
  **Windows** menu). It takes plain multichannel PCM as readily as an ADM, and
  the old name said otherwise.

- **It opens without a Project, and survives closing one.** The window used to
  belong to whichever Project window created it, so opening it made a blank
  Project first and closing that Project took the Preview with it. It is now
  the application's own window, with its own audio device. **Open Into EDL**
  and **Open Into Album View** still work with no Project open — they make one
  and carry on.

- **Fixed: Open Into EDL opened every file in the list, not the one you
  selected.** Selecting the first row and opening it brought in every other
  master you happened to have loaded for inspection.

- **Fixed: opening a plain PCM master created the EDL but put nothing in it.**
  It now arrives as one track carrying the file — the shape a rendered
  programme has — with no "split this into one track per channel?" question,
  which is the wrong question for a finished master. The same fault, and the
  same fix, applied to adding one to an Album View.

- **Fixed: a multichannel PCM master was routed as if it were stereo.** Its
  channels were numbered against whichever layout the *previous* file had left
  behind — or against Stereo, on the first file of a session — so an eight
  channel master fed L, R, L, R, L, R, L, R. That is why the object viewer
  showed no speakers for one, and why the Layout list's **Out** column only
  looked right some of the time.

- **Loudness is now measured, not just declared.** The meter was never switched
  on, so the pane could only repeat what the file's `bext` chunk claimed about
  itself. It now measures the material as it plays, resetting at each Play, and
  the pane title says which of the two you are reading.

- **Fixed: the loudness figures measured a 7.1 file as if it were stereo.** The
  measurement is built for a fixed channel geometry and was built once, at
  startup, before any file was loaded.

- **Fixed: the playhead never moved during playback**, and the **sample rate**
  never appeared — it was reading the Project's rate, which this window does
  not have, rather than the file's own.

- **The sample rate says whether it is being converted.** Green when the file's
  rate is the device's own rate, **yellow** when it is not and the material is
  being sample-rate converted for monitoring — worth knowing before you judge a
  master by what you are hearing.

- **The Monitor layout names a plain PCM master's channels.** A bare
  multichannel file carries no channel names, so the layout you say you are
  monitoring in is the only thing that can say which speaker channel 5 is.
  Switching Monitor renames the rows. An ADM names its own tracks and is left
  alone.

- **Select more than one file at a time** and open them all — one EDL each, or
  all onto an album. **Edit Metadata** takes the first of them. Inspecting
  stays one at a time: the last row you click is what the read-outs, the Layout
  list, the object viewer and playback show.

- **Fixed: the Layout list kept showing a file you had closed.** Selecting a
  file that had not been read yet left the previous one's tracks on screen for
  the whole time it was reading — so closing an ADM and picking a plain PCM
  master still showed the ADM's layout.

- **The object viewer's controls** sit under the viewer in two rows — the view
  angles above, the checkboxes below — so they fit the narrower column.

- **Layout list:** tooltips throughout, "Grp" is now **Edit Group** and wide
  enough to read, and Option-clicking **M** or **S** applies to the whole edit
  group — including the row you clicked.

- **The Desk** now fills half the window, so a 7.1.4 master's twelve channels
  have room, and carries the **main fader**, **DIM** and the **sample rate**.
  Minimum window width is 1000.

- **Space bar** plays and stops. **Delete** removes the selected file. The file
  list is remembered between launches.

---

### Fixes

- **Fixed: a crash during playback.** The audio thread looked up a track by an
  index captured when the engine was last built, without checking it still
  existed. Removing tracks — which the Preview does every time you select a
  different file — could leave that index pointing past the end. This could
  happen in an EDL too, not only in the Preview.

- **Fixed: a crash on closing Audio I/O Settings.** The device manager was
  released while the settings panel showing it was still alive. With the
  Preview open, that dialog now configures the Preview's own device, so
  changing the device moves what you are listening to rather than leaving it
  behind on the old one.

---

### Known limitations

- **Recording (new in 1.1.62)** has been used for real takes but not across
  many interfaces, sample rates and channel counts. Please report anything odd,
  especially dropouts.
- No audible input monitoring; armed tracks meter their input but do not pass
  it to the outputs.
- Latency compensation covers the computed digital path only.
- The **Desk** is still master-bus only; per-track strips are designed, not
  built.
- The Preview window does not yet carry track names, edit groups or mute/solo
  across when you open a master — only the Skip choices and the layouts.
- The Track View pop-up features individual **tracks**; featuring a whole edit
  group or the bed as a unit is not built.
- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-63"></a>
## 1.1.63 — 2026-09-10

A new **Preview ADM** window, and fixes for ADM import on top of 1.1.62's recording.

### Preview ADM

**File > Import > Preview ADM...** opens a master so you can look at it, listen
to it and decide how it should come in — before importing it.

- **Load any number of masters**, by dropping them on the window or with **Open
  ADM**. ADMs and plain multichannel PCM alike: a speaker-based master is a
  master too.
- **See what is in it** — sample rate, bit depth, duration, start time,
  channels, objects, beds and the bed's layout, plus the loudness the file
  declares about itself.
- **Play it**, with its own transport and level meters, and choose the
  **Source** and **Monitor** layouts to hear it folded the way you will
  deliver it.
- **Watch its objects move** in the object viewer, with the same view controls
  the Objects window has.
- **Skip the channels you do not want** — tick Skip in the Layout list and
  those tracks are not created when you open it.
- **Open Into EDL** or **Open Into Album View** when you are satisfied.

Opening into an EDL is fast: the window has already read the file, so it hands
over what it parsed rather than making the import read an Atmos master a second
time.

Import ADM is unchanged and still there — previewing is something you choose,
not a step added to every import.

---

### ADM import

- **Fixed: importing a large ADM master hung the application.** Every track the
  import added told the audio engine to rebuild, and each rebuild re-read every
  clip — which, for an ADM, means JUCE re-parsing the file's entire `axml`
  metadata block each time. On a 122-object master that was well over a hundred
  rebuilds, each re-parsing tens of thousands of nodes, all on the thread that
  draws the window. The import now tells the engine once, when it is done.

  If you saw soundBlade stop responding part-way through importing an Atmos
  master, this was why.

- **Fixed: the ADM's own speaker layout was read but never applied.** Importing
  a 7.1.2 master left the EDL header's layout button showing the previous
  layout — and, less visibly, left the Master Bus still folding to it. The
  Speaker Layout dialog showed the right answer while the monitoring did not.

  The authored layout is now applied on import: the button, the dialog and what
  you hear agree.

### Interface

- The **Files/Marks/Layout** window opens at **480 × 600**, rather than the
  narrower size inherited from the docked panel it replaced. A window you have
  resized keeps your size; one smaller than this is grown to it.

---

### Known limitations

- **Recording (new in 1.1.62)** has been used for real takes but not across
  many interfaces, sample rates and channel counts. Please report anything odd,
  especially dropouts.
- No audible input monitoring; armed tracks meter their input but do not pass
  it to the outputs.
- Latency compensation covers the computed digital path only.
- The **Desk** is still master-bus only; per-track strips are designed, not
  built.
- The Preview window does not yet carry track names, edit groups or mute/solo
  across when you open a master — only the Skip choices and the layouts.
- Its loudness figures are what the file DECLARES, not a measurement.
- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-62"></a>
## 1.1.62 — 2026-09-09

**Recording.** soundBlade can now record into the EDL.

### Recording

Until this release soundBlade could not see audio input at all — the audio
device was opened with no input channels, and playback discarded any that
arrived. This is the whole feature, built end to end.

#### Arming a track

- **R** in the track header arms a track. It blinks while armed and goes solid
  while rolling.
- Pick the input in the header's **"In"** box, which reads like the Output
  selector beside it.
- **An armed track's meter shows its INPUT**, from the moment it is armed —
  before, during and after a take. An ordinary track's meter shows its playback
  output as before.
- Metering only: an armed track does **not** pass input through to the outputs.

#### Taking a take

- **Record** on the transport (left of Play/Pause) is record-*enable*. Then
  **Play** records until Stop.
- **Cmd+Space** does **AutoPunch**: it rolls the selection and punches between
  the Start/End record points inside it, or records across the whole selection
  when it holds none. Cmd+Space already meant "play the selection" — AutoPunch
  is that same gesture with record-enable on.
- On stop soundBlade **asks whether to insert** the take. Each one lands on its
  own new track at its true start, latency compensated, as one undoable step. A
  punched pass makes one clip per window.

#### Where takes are written

**Windows ▸ New Soundfile Settings** — path, name, take number, format and bit
depth, in the legacy layout. The name is built from tags, the way Export's is.
BWF adds the bext fields, and they are written into the file.

#### Latency

The computed digital round trip — buffers plus the device's own reported input
and output latency — is compensated automatically, so a take lands where it was
played rather than late by the buffer size. Analog gear outside that path is
not measured; see Known limitations.

### Elsewhere

- **Tooltips** on the transport, navigation and overview-bar controls.
- **Zoom buttons** read correctly: the caret zooms out, the v zooms in.
- The chosen **input device is remembered** between launches.

---

### Known limitations

- **Recording is new.** It has been used for real takes but not yet across
  interfaces, sample rates and channel counts — please report anything odd,
  especially dropouts.
- **No audible input monitoring.** Armed tracks meter their input but do not
  pass it to the outputs.
- **Latency compensation covers the digital path only.** External analog gear
  adds delay soundBlade cannot measure.
- **Edit Recording** (continuous flush) is shown but disabled.
- The **Desk** is still master-bus only; per-track strips with input/output
  metering and Solo/Mute/Record are designed but not built.
- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-61"></a>
## 1.1.61 — 2026-09-07

A **Custom** source layout, for material whose channel order matches no standard layout.

### Source layout

The Source layout on an EDL header says what the material *is* — the layout its
output channels are folded *from*. Until now it offered Off, Auto, or a named
layout, and a named layout assumes the material is in that layout's own speaker
order.

**Source ▸ Custom…** removes that assumption. Pick the geometry the material
uses — 7.1.4, 5.1.2, whatever it is — then say which channel of the material
carries each speaker.

- **It is the escape hatch.** A delivery from another tool routinely carries
  the right speakers in a different channel order, and until now the only
  options were to accept a wrong fold or re-order the files by hand.
- **It is also the fallback for filename detection.** Dropping a set of mono
  stems reads speaker names off the filenames, but only names soundBlade
  knows; a house convention that spells them differently can now be mapped by
  hand instead.
- **A speaker with no channel mapped is silent**, rather than taking whatever
  happens to sit in that slot.
- **The mapping is saved with the EDL**, geometry and order together.
- **Switching the Source away from Custom clears it**, so no stale order can
  survive for a layout you are no longer using.

The list is deliberately not limited to what your interface can play: the point
of a source layout is describing material authored wider than the rig
monitoring it.

---

### Known limitations

- The channel column in the Custom Source window is labelled in output terms,
  inherited from the speaker-layout editor it shares. It means "which channel
  of the material carries this speaker".
- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- Speaker-layout renders have not been verified against the Dolby renderer.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-60"></a>
## 1.1.60 — 2026-09-07

Fixes export name tags not being remembered, makes them per project, and teaches the Auto source layout to read speaker names off dropped filenames.

### Export

- **Fixed: the name-tag template was not saved.** It was only written when you
  pressed Export, so a template built and then not exported — which is most of
  the time you build one — was gone when the window reopened. It is now saved
  the moment a pill is dragged in, out or along the row, or a free-text tag is
  edited.

  The order of the tags and the contents of the two free-text pills both
  persist.

- **The template belongs to the Project.** A naming scheme is often a client's
  delivery spec rather than a house style, and the free-text tags in particular
  carry job-specific text that should not follow you into the next Project.

  A Project with no template of its own falls back to the app-wide one, so a
  new Project still inherits the last scheme you used rather than starting
  blank. The Project's own copy is written when the Project is saved.

### Importing

- **Dropping a set of mono stems reads the layout from their filenames.** This
  refines the **Auto** source layout, which until now inferred purely from the
  channel count — a guess that cannot tell 7.1 from 5.1.2, since both have
  eight channels.

  Two forms are recognised:

  - **Speaker names** — `Mix_L`, `Mix_C`, `Mix_LFE`, `Mix_LSS`, `Mix_RTF`…
    matched case-insensitively against soundBlade's own speaker names. This
    form is definitive: a set carrying `Lss`/`Rss` is 7.1, one carrying
    `Ltf`/`Rtf` without side surrounds is 5.1.2. The EDL's Source layout is
    set accordingly.
  - **Ordinals** — `Mix_01` … `Mix_08`. These give order only, never identity,
    so the layout is still inferred from the count; the files simply land in
    the right order instead of whatever order the drop arrived in.

  The tracks are **created in layout order**, so outputs stay at their defaults
  and the EDL reads as an ordinary stem set rather than a stack of hand-routed
  tracks.

  It is all or nothing: the names must cover a layout exactly — every speaker
  present, none spare, none twice — or nothing is reordered. And it only fills
  in a Source layout set to **Auto**; an explicit choice is never overridden.

  **The monitor speaker layout is never touched.** This is evidence about what
  the material is, not about what you are listening on.

---

### Known limitations

- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
  Fine for monitoring; a dedicated 44.1 deliverable deserves scrutiny.
- Tag separator is a fixed underscore.
- Filename detection recognises soundBlade's own speaker names; a house
  convention that spells them differently will not be matched. A user-defined
  **Custom** source mapping is designed but not yet built.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- Speaker-layout renders have not been verified against the Dolby renderer.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-59"></a>
## 1.1.59 — 2026-09-07

Export window tidying, layout names in filenames, and Analog Black to Marks working from a clip selection.

### Export

- **Speaker layouts read as `51` and `714` in filenames**, not `5.1` or
  `5_1`. Dots come out rather than becoming underscores, which keeps the
  underscore meaning one thing — the separator between tags — instead of
  doubling as a decimal point. This matches how the Create Folders set names
  were already written.

- **Stems sits with the layouts**, to the right of 9.1.6, instead of on its own
  row above the heading. It is the same kind of choice as a layout — what shape
  the output takes — and one of them is always ticked.

- **Album moved** to below Speaker Layouts and above Originator. It is a
  metadata field, written into the file as one, so it belongs at the head of
  that group rather than among the controls that decide how the output is cut.

- **A rule separates the two halves** of the window: everything above it
  decides the files themselves — name, format, cuts, layouts — and everything
  below is metadata stamped inside them.

### Marks

- **Analog Black to Marks works from selected clips**, not only from a time
  selection. Selected clips take precedence, matching the rule the other
  mark-generating commands already follow ("you must first select either
  segments or a region"), so an old time selection left lying around no longer
  overrides clips you have just picked. The span measured is the clips' own.

---

### Known limitations

- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
  Fine for monitoring; a dedicated 44.1 deliverable deserves scrutiny.
- Tag separator is a fixed underscore.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- Speaker-layout renders have not been verified against the Dolby renderer.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-58"></a>
## 1.1.58 — 2026-09-07

Every exported file now names itself from its own facts.

### Export filename tags

- **Each output is named from its own rate, bit depth and layout.** A Multiple
  Export fans one press out into a file per rate/depth combination and per
  speaker layout, and each one now renders the name template for itself:

  ```
  48-24/MyMix_48k_24.wav
  44-24/MyMix_44.1k_24.wav
  44-16/MyMix_44.1k_16.wav
  ```

  Previously the name was assembled once in the dialog, so all three carried
  the same one — the 44.1/16 file was labelled 48k/24, wrongly and
  convincingly. The rate in a filename now comes from the same value used to
  write the file, so the two cannot disagree.

  Sample rates read as `48k`, `44.1k`, `96k`, `88.2k` — the decimal appears
  only when there is one.

- **The Layout tag is no longer doubled.** The export used to append the layout
  to every filename; with a Layout pill in your template you have already said
  where it goes. Without a template, the old suffix is unchanged.

- **Split at Marks composes with tags.** The Name tag resolves to each track's
  own title, so one template names a whole numbered album correctly across
  every rate/depth set.

- **Create Folders uses the plain name** for its set folder, rather than the
  assembled one — a folder called `MyMix_48k_24` inside `44-16` would be worse
  than no name at all.

---

### Known limitations

- Sample-rate conversion for a Multiple Export uses Lagrange interpolation.
  Fine for monitoring; a dedicated 44.1 deliverable deserves scrutiny.
- Tag separator is a fixed underscore.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- Speaker-layout renders have not been verified against the Dolby renderer.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-57"></a>
## 1.1.57 — 2026-09-07

Build export filenames from draggable tags, ADM export gives every object the same end time, and Sync To Matching moves the Destination. (1.1.56 was built but never published — a release-script failure. Everything intended for it is here.)

### Export filename tags

**Export Sound File** gains two rows of pills under **Name:**.

- **The lower row is the palette**; the upper row is the name being built.
- **Drag a pill up** to use it, along the row to reorder, back down to remove.
  The order in that row *is* the order in the filename.
- **The Name field shows the result** as you build it, and goes read-only while
  a template is active. Clear the template and your typed name comes back,
  editable.

Seven tags:

| Tag | What it writes |
|---|---|
| **Name** | the name you typed |
| **SR** | the sample rate |
| **Date** | the export date |
| **Bit Depth** | 16 / 24 / 32 |
| **Layout** | the speaker layout — Stereo, 5.1, 7.1.4 |
| **two free-text tags** | whatever you type into them — double-click to set |

- **Layout follows the Speaker Layouts boxes live.** With more than one layout
  ticked it shows the first and draws **italic**, because each written file
  gets its own.
- The free-text pills are a **different colour** to the rest, so at a glance
  you can see which parts of a name are literal text and which are values the
  export fills in.
- **The template is remembered between exports**, free text included. A naming
  scheme is a house style, not a per-export decision. It is saved when you
  press Export, so a half-built template you abandoned is not the one that
  comes back.

### ADM export

- **Every object now ends at the same time.** Objects that finished earlier are
  held to the latest soundfile end on the timeline, so the written ADM no
  longer declares different extents over identical-length audio — something
  renderers treat inconsistently and conformance checkers reject. The audio is
  untouched: this is metadata, and the PCM was always uniform.

  Objects are only ever extended, never shortened.

### Sync To Matching

- **The Destination moves and the Source stays put.** The Source selection is
  the passage you have picked out as correct, so it is the thing that should
  not move. (soundBlade HD moved the Source; this is deliberately the reverse.)
- A Destination clip pushed before zero is **trimmed at the front** rather than
  clamped, so the alignment holds.

---

### Known limitations

- The **SR** tag currently writes the project's rate. A Multiple Export that
  writes 48k and 44.1k from one press names both files from the same rate.
- **Layout** is blank until a speaker layout is ticked.
- Tag separator is a fixed underscore.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- Speaker-layout renders have not been verified against the Dolby renderer.
- **ADM export** does not carry album or track titles.

[Back to the list of versions](#versions)

---

<a name="v1-1-55"></a>
## 1.1.55 — 2026-09-07

**Sync To Matching** — line up EDLs against a reference by measuring the audio rather than trusting nominal positions. Plus a round of Album Mode fixes from testing 1.1.54, and the read speed-up that 1.1.54 announced but did not actually deliver.

### Sync To Matching

**Edit > Sync To Matching** measures where audio actually lines up, rather than
trusting where it was put. It works two ways, and picks between them itself.

#### Between tracks, in one EDL

The manual's own behaviour. Tag one group of tracks **Edit Target > Source**
and another **Edit Target > Destination**, make a time selection over a passage
the two share, and run it.

- The two sides are correlated against each other over that selection.
- **The Destination moves; the Source stays put.** The Source selection is the
  passage you have picked out as correct, so it is the thing that should not
  move. (This is the reverse of soundBlade HD, which moved the Source.)
- A Destination clip pushed before zero is **trimmed at the front** rather than
  clamped, so the alignment holds.
- One undoable step.

#### Across EDLs, for an album

Aligns every programme EDL against one reference EDL, by the same measurement.

The intended workflow: assemble an album to get everything roughly in place,
drop in a reference master, then Sync To Matching to put each programme
exactly where the reference says it goes.

- **You pick the reference EDL.** Usually the Stereo album — which is now the
  topmost EDL in an assembled project for exactly this reason.
- **The selection says where to look and what to look for.** A time selection
  on the reference is the passage to search within; a selection on a programme
  is the passage to find. The selected track picks which channel is compared,
  falling back to the EDL's first track.
- **Without a selection on a programme**, it takes a 10-second excerpt from
  where that programme currently starts and searches ±15 seconds around it —
  which is what lets a whole album run after selecting on the reference alone.
- **Each move is one undoable step.**
- **A programme that doesn't clear the confidence threshold is left alone** and
  reported. A nominal position is at least a reasoned guess; an unmatched
  correlation peak is not.

The command is greyed out until there is a time selection — a command that
quietly guesses its own window is worse than one that waits to be told where to
look.

### Album Mode

Fixes and refinements from testing 1.1.54.

- **The options dialog now comes first.** Speaker layouts and programme spacing
  are asked before the import runs, not after the EDLs already exist.
- **Album EDLs are ordered narrowest first** — Stereo, then 5.1, then 7.1.4 —
  so the one most likely to be used as the Sync reference sits at the top of
  the project rather than under the wide layouts.
- **Fixed: programmes landing in the wrong place in the wider albums.**
  Alignment was keyed by EDL position, so inserting an album at the top shifted
  every index beneath it and the 5.1 album drifted out of step with the Stereo.
- **Fixed: the ADM EDLs were a programme out of step.** Each source EDL's
  start time was recorded against its neighbour in the list, so the ADMs sat
  one programme late and the last was left at 0:00. Every ADM EDL now starts
  where its own programme starts in the album -- the first at 0:00, the second
  where the second programme begins -- saved as a real edit, so scrubbing down
  the EDL stack lines everything up.
- **Tracks appear while the import runs**, with the Layout tab shown, instead
  of the window staying empty until the whole batch finishes.
- **The album is one track** per layout, programmes end to end.
- **ADM tracks come in at the smallest height**, album tracks at small.
- **Zoom Lock is on** for every EDL in an assembled project.

### Performance

- **Fixed: the wide-file read speed-up from 1.1.54 was not actually working.**
  The direct reader re-opened the file and re-parsed its RIFF chunks on every
  65,536-sample block — around 12,000 times per render — which cancelled out
  most of what it gained. The parse now happens once and the handle is kept.

  Measured on ordinary ADM masters: **24× faster import, 20× faster render.**

### Desk

- **A plug-in spread across the Master Bus now covers every channel, LFE
  included.** LFE used to be skipped. It is what's wanted almost every time,
  and the per-channel placement controls are still there for when it isn't.

### Interface

- The EDL header's name and sample-rate fields are wider, and the Zoom Lock and
  Play Lock buttons have moved right to suit.

---

### Known limitations

- The correlation behind Sync To Matching has not yet been checked against a
  known delay — a file against a deliberately delayed copy of itself, where the
  right answer is known exactly.
- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- Speaker-layout renders use soundBlade's own panner; they have not yet been
  verified against the Dolby renderer.
- **ADM export** does not carry the album or track titles.
- Album programmes are rendered **one at a time**. On a large album with many
  objects this takes a while.

[Back to the list of versions](#versions)

---

<a name="v1-1-54"></a>
## 1.1.54 — 2026-09-07

Album Mode: import several ADMs at once and assemble them into one album, each programme rendered to the speaker layout you choose and every ADM kept open to drill into. Plus a large speed-up to reading wide multi-channel files.

### Album Mode

**File > Import > Assemble Album...** takes a set of ADMs and builds an album
from them.

- **Choose several ADMs at once.** Each becomes its own EDL in a brand-new
  Project, imported one after another with progress across the whole batch.
- **You name the Project** as part of the flow — the rendered programmes are
  written to a **Renders** folder beside it, and the album refers to them
  there.
- **Pick the speaker layouts** to render to; more than one is fine, and the
  choice is remembered.
- **Choose how programmes meet** — AutoSpace (using the AutoSpacing Duration
  from Project Settings), Butt Splice, or Cross-fade. Also remembered.
- **The album appears at the top** of the EDL stack, one track per programme,
  and the source EDLs collapse beneath it.

**The ADMs are kept, not consumed.** Every programme stays a full EDL with its
bed and objects intact, so you can open one, change a pan or a plug-in, and
run Assemble Album again — that programme is re-rendered and replaced in place,
keeping its position in the album.

A separate Album EDL is made for each layout, since prints of different channel
counts cannot share a track.

**File > Import > Import ADM...** also takes several files now, each becoming
its own EDL, without any rendering.

Both commands are available with no Project open.

### Performance

- **Reading wide multi-channel files is dramatically faster.** Pulling one
  channel out of a file previously decoded every channel to get it, and did so
  through a small fixed buffer that grows less efficient the wider the file is:
  on a 122-channel ADM master it managed 15 sample frames per read, against 960
  on a stereo file. An album render was spending **799 of its 802 seconds**
  reading. Single channels are now read directly, in large blocks.

  Verified bit-identical: an export made before and after the change matches
  byte for byte across the whole audio payload.

### Importing

- **Fixed: dropping several files and choosing separate tracks scattered
  them.** Two files dropped on track 1 put one on track 1 and the other on a
  new track at the bottom of the EDL. They now land on adjacent tracks — 1 and
  2 — appending only when the tracks below are occupied.

### Editing

- **Option-P opens the selected track's plug-in slots**, the keyboard
  equivalent of the track header's "P" button. It works across a multi-track
  selection.

---

### Known limitations

- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- Speaker-layout renders use soundBlade's own panner; they have not yet been
  verified against the Dolby renderer.
- **ADM export** does not carry the album or track titles.
- Album programmes are rendered **one at a time**. On a large album with many
  objects this takes a while.

[Back to the list of versions](#versions)

---

<a name="v1-1-53"></a>
## 1.1.53 — 2026-09-07

Export Tracks comes to the Export Sound File window: split a master at its marks into one file per track, carrying each track's own title and ISRC. Change Plug-in now actually changes the plug-in, and the export window no longer blocks the EDL while it is open.

### Export

- **Split at Marks.** One file per marked track, from a Start mark to its own
  End mark — so the pause between an End and the next Start is written to no
  file at all. The file takes its name from the mark, falling back to
  "Track 3" for a mark with no title.
- **Add Track Number** prefixes each file with its number: `01 Song Name.wav`.
- **ISRC: From Each Mark.** Each file carries the ISRC of the mark that opens
  its track, as entered in the Mark Tab, instead of one code shared by every
  file.
- **CD Frame (1/75s)** rounds each region's start and end to a CD frame. Off
  by default — it only matters when the files are destined for a disc.
- **Album**, and each track's title, are written into every exported file.
  Leave a field blank and no tag is written for it. The album is remembered
  between exports.
- **Create Folders** gives each format its own folder under one named for the
  export: `Untitled Export/Untitled Export_Stereo`, `..._714`, `..._Stems`.
  It nests inside a Multiple Export rate/depth folder, so both can be used at
  once.
- **The export window no longer blocks the EDL.** Leave it open, set or adjust
  a selection, then export — the selection is read when you press Export, not
  when the window opened.
- **The window now opens on the project's own speaker layout** rather than on
  Stems. A project set to Custom still opens on Stems, since Custom has no
  layout of its own to preselect.

Split at Marks, Add Track Number, CD Frame and the ISRC source are only
available when the EDL actually has marked tracks to split at.

### Plug-ins

- **Fixed: Change Plug-in left the old plug-in running.** On the Master Desk
  window the change never reached the audio engine at all — the previous
  plug-in kept processing and its editor kept showing the old interface. On
  EDL Desk Events the editor simply never came back after the change.
  Changing a plug-in whose editor is open now reopens it on the new one;
  changing one whose editor is closed leaves it closed.
- **Change Plug-in now checks the incoming plug-in the same way Add does**, so
  a plug-in that hangs on load cannot be brought in through the change path.

### Desk

- **Click DITHER to switch monitoring dither off and on.** It stays in step
  with Project Settings — both write the same setting — and turning it back on
  restores the mode it was in, rather than always returning to Automatic.
  Monitoring only: the export dither mode is untouched.

### Marks

- **Return moves to the next track's title.** Entering titles down the column
  now works: Return commits and opens the next track's cell with its text
  selected, skipping Index and TrackEnd rows. This never worked before.
- **Fixed: the track number could be stored into the title.** The Name column
  shows "3- Song Title", and committing a cell without retyping it stored that
  whole string as the title, which then redrew as "3- 3- Song Title".

### Marks window

- **The Marks tab opens big enough to work in.** Bringing it to the front now
  sizes the window to fit the whole track list rather than showing a few rows
  and a scrollbar, and widens it so the Title, Artist and ISRC columns are on
  screen. It only ever grows — a window you have sized yourself is left alone —
  and never grows past the display. The size is remembered, so it is asked for
  once.

### Importing

- **Dropping several multi-channel files asks once.** The split prompt offers
  "Do this for all files" whenever more than one file is dropped.
- **You now choose where split channels go** — the selected track or new
  tracks — and the choice is remembered. It previously guessed, and appended
  new tracks whenever the tracks it wanted were not all free.
- **Fixed: a split was placed relative to the wrong track.** It followed the
  selected track rather than the track the file was dropped on, which are not
  the same thing — dropping on a lane does not select it.

---

### Known limitations

- Renders ignore **Solo**, and do not apply the **Main fader** or **Dim**.
- Speaker-layout renders use soundBlade's own panner; they have not yet been
  verified against the Dolby renderer.
- **ADM export** does not yet carry the album or track titles. It is a
  separate command that rewrites an existing ADM, and does not pass through
  the Export Sound File window.

[Back to the list of versions](#versions)

---

<a name="v1-1-52"></a>
## 1.1.52 — 2026-09-05

The Files/Marks/Layout panel becomes its own window, the soundBlade menu works with no Project open, and a Master Bus plug-in narrower than the bus now covers all of it.

### Master Bus

- **A plug-in narrower than the Master Bus now covers the whole bus.** A
  stereo plug-in on a 7.1.4 bus used to process L/R and leave the other ten
  channels dry. It is now placed several times over, all linked to a single
  editor, so one plug-in covers the bus: **(L,R)**, **(Lss,Rss)**,
  **(Lrs,Rrs)**, **(Ltf,Rtf)**, **(Ltm,Rtm)** — plus **C on its own in
  mono**, where the plug-in offers a mono layout.
- **You're asked once how it should be laid out** — spread across the bus,
  or a single instance on just the channels you pick (chosen by speaker
  name, not channel number). The choice is saved with the EDL and reused
  when you reopen it.
- **LFE is deliberately left unprocessed** when spreading.
- **Everything stays in sync.** Moving a control, or loading a preset inside
  the plug-in, applies to every copy. Recorded automation drives all of
  them together.
- **Latency is handled per channel.** Any channel a plug-in doesn't process
  — LFE, or a lone channel when the plug-in has no mono layout — passes
  through and is delay-compensated, so it stays aligned with the channels
  that are processed.

### Export

- **Fixed: a printed master could differ from what you monitored.** Three
  separate causes: the Master Bus width was treated as stereo on export
  regardless of the real layout; a plug-in that couldn't take the bus width
  was silently left out of the print entirely; and the chain was printed as
  one instance across the full width rather than the way it actually runs.
  Exports now print the master chain exactly as the engine plays it.

### Files/Marks/Layout

- **The browser panel down the left side is now a window of its own**, with
  **Files**, **Marks** and **Layout** items in the Windows menu — each opens
  the window and brings up that tab. Its position and whether it was open
  are remembered and restored on launch. The collapse button is gone; the
  Project window is now entirely timeline.

### Elsewhere

- **Application Settings, Audio I/O Settings and Send Report stay in the
  soundBlade menu with no Project open** — previously the whole menu
  reverted to a bare one the moment the last Project window closed.
- **Launching with nothing to reopen now starts from your saved default
  Project** rather than four blank starter tracks. A Project you were
  working on still reopens ahead of it, as before.
- **Fixed: removing a Master Bus plug-in left it running.** Its instance was
  never actually torn down, so it kept processing audio for the rest of the
  session.
- **Fixed: pasting tracks into a new, empty EDL now sets its sample rate**
  from the pasted clips, as dropping a file already did.
- **Fixed: the Project Settings Speakers tab was cut off**, hiding the lower
  speakers and the Binaural section below them.

---

### For testers — Master Bus

The parts worth deliberate listening, and why:

- **Is a mono centre right?** C now gets its own instance rather than
  sharing one with a partner, so on a compressor or limiter it has its own
  detector — it won't duck along with the surrounds. That's a mixing
  judgement, not just a technical one, and it's the thing most worth an
  opinion.
- **Should LFE really be excluded?** It's currently never processed when
  spreading. If that's wrong, it's a one-line change.
- **Does a plug-in without a mono layout behave acceptably?** In that case C
  falls back to passing through unprocessed (delay-compensated). Worth
  checking which of your plug-ins actually offer mono.
- **Null-test an export against the monitored mix.** Three separate export
  bugs were fixed here, so this is the least proven path of the lot.
- **Latency**, using something with real delay — a linear-phase EQ or a
  look-ahead limiter. Any misalignment between processed and pass-through
  channels shows up as comb filtering, most audibly on centre-heavy
  material.

[Back to the list of versions](#versions)

---

<a name="v1-1-51"></a>
## 1.1.51 — 2026-09-04

Fixes for dropping multiple files, the Desk window, Project Settings, and ADM import's Speaker Layout.

### Dropping files

- **Fixed: "At Timestamps" placement always fanned out one new track per
  file**, even when every file was dropped on a single lane specifically
  to keep them on one track. Split into two explicit choices instead: "At
  Timestamps (One Track)" keeps everything on the track you dropped on,
  each file at its own embedded time; "At Timestamps (Separate Tracks)" is
  the old one-new-track-per-file behavior, still available for whoever
  wants it.

### Desk window

- **Fixed: the Desk window could end up the wrong size after a Speaker
  Layout change that alters the channel count** (e.g. Stereo → 7.1.4) —
  resizing the existing window in place wasn't reliable across very
  different widths. It's now rebuilt fresh whenever the count actually
  changes, keeping its position. A layout change that doesn't add or
  remove channels still just resizes, as before.

### ADM import

- **Fixed: an imported ADM's Speaker/Monitor Layout could stay stuck on
  Stereo** regardless of the file's actual bed width, since a brand-new
  EDL's layout was silently downgraded to whatever the current audio
  device could physically output before the file's own content was even
  read. The Monitor Layout is now set from the ADM's own bed, the same way
  Source Layout already was. If the current device genuinely can't carry
  that many outputs, you're asked whether to open Audio I/O Settings
  rather than silently ending up on Stereo with no explanation.
- **Pasting tracks into a brand-new, empty EDL now sets its sample rate**
  from the pasted clips, the same way dropping a file already did — it
  no longer stays unset until something else establishes one.

### Project Settings

- **Fixed: the Speakers tab could be cut off for wider layouts**, hiding
  the lower speakers and the Binaural section below them regardless of how
  many speakers the selected layout actually has. The dialog now sizes
  itself correctly for every layout again.

[Back to the list of versions](#versions)

---

<a name="v1-1-50"></a>
## 1.1.50 — 2026-09-03

A plug-in processing bug traced all the way from Export to the Master Bus, a much faster ADM import/reopen, and a handful of Desk window fixes.

### Plug-in processing

- **Fixed: "Change Plug-in" could leave the old plug-in still processing.**
  Its editor showed the newly chosen plug-in, but audio kept running through
  the one it replaced — fixed for track, group-shared, and Master Bus
  plug-ins alike.
- **Fixed: a Master Bus or group-shared plug-in could sit ready but silent**
  until something unrelated (opening its editor, any other edit) happened
  to nudge the engine. It now starts processing the moment it's ready.
- **Fixed: multi-bus plug-ins (e.g. a sidechain compressor) were being
  silently declined**, both live and on Export — a regression from recent
  branch work.
- **New: a Master Bus plug-in that can't take the full bus width** (a
  stereo plug-in on a 5.1.2 bus, say) now asks whether to open it anyway —
  it processes just the channels it supports, correctly latency-compensated
  per channel, instead of refusing outright.

### Export

- **Fixed: Export Selection, Export Selection and Insert, and Export Sound
  File never printed any plug-in, on any track.** Export EDL and DDP export
  were unaffected.
- **Fixed a VST3 export crash risk** from required setup work running on
  the wrong thread.

### ADM import

- **Importing an ADM into an already-open Project now asks** whether to add
  it as a new EDL there or start a fresh Project — and a second (or third)
  ADM can now land in the same Project this way.
- **Reopening a large ADM-derived Project is dramatically faster.** A
  60-track EDL that took nearly two minutes to reopen now takes seconds —
  it was paying for a full rebuild after every single track and clip
  loaded, instead of once at the end.
- **The metadata-parsing step now shows honest progress** instead of
  looking stuck.
- **Import ADM/EDL/Project are available from the File menu** even with no
  Project window open.

### Desk window

- The meter row is properly sized for its own layout again (plug-in slots,
  meters, Solo/Mute), and no longer reverts to a stale size on reopen.
- The Master Volume fader sits slightly clear of the window's top edge.

### Elsewhere

- The Layout tab redraws immediately when a track's Edit Group changes.
- Zoom Lock and Play Lock now save with each EDL and restore when reopened.
- Open Recent Project no longer opens a stray blank window alongside the
  real one.
- The EDL name field no longer overlaps the Zoom Lock button.

[Back to the list of versions](#versions)

---

<a name="v1-1-49"></a>
## 1.1.49 — 2026-08-30

Dragging segments now has one clear set of rules, plus fixes to clip gain, the lane's context menu, and the Delete key.

### Dragging a segment: what a drop means

Everything about dropping a segment on a track comes down to two questions —
**was a snap bar showing**, and **is anything already where the clip landed**.

| Drop | Result |
|---|---|
| On a **blue** bar, into a gap | The clip moves. Nothing else changes. |
| On a **blue** bar, at a junction between two segments | The clip is inserted flush there; that segment and everything after it move right. |
| On a **red** bar, at a junction | The same, with the AutoSpacing Duration of space left in front. |
| **Shift** held, no bar | The clip is cut into the segment under it: the right-hand half becomes a new clip, both new edges get the Default CrossFade, and everything from there moves right. |
| Plain drop, no bar | The clip simply overlaps what's underneath. Nothing ripples, no fade is rewritten. |

**Nothing is ever pulled earlier in time.** A ripple only ever moves clips to
the right, and only clips at or after the insert point.

**Dragging to close a gap just closes it.** Snapping a segment up against its
neighbour — in either direction — moves that one segment and leaves the rest of
the track alone.

**Inserting between two crossfaded segments keeps their fades.** The clip going
in takes its head and tail fades from the neighbours and its edit point is
placed on theirs, so the join stays where you put it. Only a Shift-cut creates
new fades, because only a cut creates new edges.

### Snap to Zone fixes

- **The bars appear where the join is** — on the neighbour's fade edge, not on
  the dragged clip's own start. They could previously be a whole clip-length
  away from the junction they were marking.
- **The auto-spaced (red) gap starts after the fade-out**, not after the edit
  point, so it no longer begins partway inside the fade it follows. It is also
  no longer applied twice.
- **A dragged segment draws on top** of the ones it passes, instead of sliding
  underneath them.
- **Fixed: clicking a clip's title bar could ripple the whole track.** On
  crossfaded material a plain click was being read as a drop. A click now
  selects and does nothing else.

### Clip Gain

- **The waveform reflects clip gain.** Setting a clip's gain changed what
  played and what exported while the picture stayed identical.
- **Reopening the dialog shows the current value.** It only did so for a
  selection of exactly one clip — and clicking a clip in an Edit Group selects
  its siblings too, so an ordinary stereo pair always opened in Relative at
  0.00.
- Renamed from **Segment Gain** to **Clip Gain**.

### Delete

- **Delete** deletes and ripples; **Option-Delete** deletes and leaves the
  space. Cmd+Opt+D still works.
- **Fixed: Delete did nothing on a selected clip.** It reached a command that
  requires a *time range*, so with only a clip selected it silently did
  nothing.

### The lane's context menu

Rebuilt into three menus — over a clip, over a time selection, over empty track
— each listing only what applies. Conditional items (Edit Point commands,
Split/Delete Selection, DeClick, Move Clip, Ripple All) appear in a group after.

- **Create CrossFade… shows Ctrl-G**, the shortcut it actually answers to. It
  advertised a bare `S`, which stopped working when the command was rebound.
- **⌘G zooms to whatever is relevant** — the clip when one is selected, the
  time selection otherwise. ⇧⌘G still reaches Zoom to Clip directly.
- A selected clip's border is **black and thinner**, not red.

### Elsewhere

- **Ctrl+wheel zooms** without Shift, centred on the **Edit Point** rather than
  the cursor, so repeated notches converge instead of drifting.
- **Ctrl-click a locked sample rate to force a change**, when Enable SRC is on.
- **soundBlade starts in English** and stays there unless you choose otherwise.
- **File → Open Recent is present with no Project open.**
- The **Track View** button is now labelled **Tracks**; Zoom Lock and Play Lock
  sit beside the EDL name and Sample Rate.

[Back to the list of versions](#versions)

---

<a name="v1-1-48"></a>
## 1.1.48 — 2026-08-28

Resequencing by dragging segments now works as the manual describes it, plus scroll-wheel and header changes.

### Snap to Zone works

The blue and red snap bars never appeared. Three separate faults were stacked
behind that, and all are fixed.

**The snap was unreachable from the Drag Bar** — the gesture the manual names
as the way to snap. Dragging a segment by its Drag Bar took a different code
path, one that never ran the snap at all; the bars could only appear on a
modifier-drag of a clip's body, which nothing documents.

**It was skipped on any track in an Edit Group.** Clicking a clip selects its
synced siblings too, so an ordinary stereo pair never snapped — and grouped
tracks are the normal case for resequencing.

**The bar was drawn in the wrong place.** It marked the dragged clip's own
start rather than the junction being made, so it sat a whole clip-length away
when snapping a tail against the clip after it. It now draws on the
neighbour's fade edge — the landmark you are aiming at.

Snap positions are also measured from the fade edges now rather than the raw
clip extents, so butting two segments leaves each fade its own room instead of
driving one into the other.

### Drop on a bar to insert and ripple

A segment can be dragged clear across and past its neighbours, lighting each
junction it passes.

**Release while a bar shows and the clip is inserted there** — what sits at
that junction is split, and everything downstream moves later by the clip's
own length. Release anywhere else and it simply lands, overlapping whatever it
covers, as before.

Moving a clip within its own track gives its old time back: the gap it leaves
closes, so resequencing no longer grows the track by a segment each time.

**A dragged segment now draws on top** of the ones it passes, instead of
sliding underneath them.

*Known limit:* an auto-spaced (red) snap against the clip **after** the
dragged one inserts flush — the leading gap is not applied on that side.

### Scroll wheel

**Ctrl+wheel zooms**, without Shift. It now zooms around the **Edit Point**
rather than the cursor, so repeated notches converge on the place you are
working instead of drifting. With no Edit Point set it falls back to the
cursor. Ctrl+Shift still works.

A plain wheel scrolls through tracks and on into the next EDL; Shift+wheel
pans left and right. Both unchanged.

### Delete and Option-Delete

**Delete** now deletes and ripples — closing the gap, which is what
resequencing wants nearly every time. **Option-Delete** deletes and leaves the
space. Cmd+Opt+D still works.

This takes bare Delete away from **Cut**, which had it so that a Delete always
left something on the clipboard. Cmd+X is unchanged.

### Sample rate

**Ctrl-click a locked sample rate to force a change.** The lock exists because
the files already in the EDL were read at that rate, which is a reason to make
the change deliberate rather than impossible — an EDL settled by the wrong
first file previously had no way back.

It asks first, and is offered only when **Enable SRC** is already on: without
conversion those files would simply play at the wrong speed. With SRC off, the
Ctrl-click says so and names where to turn it on.

### Language

**soundBlade now starts in English** and stays there unless you choose
otherwise in Preferences. It used to follow the operating system, so a German
Mac opened a German-titled app nobody had asked for — and only partly
translated, since the translation files cover a fraction of the interface. The
"System Default" option has been removed; the choice is now recorded on first
launch.

### Open Recent with nothing open

**File → Open Recent is now present when no Project is open**, listing recent
Projects, EDLs and media exactly as it does inside a window. It previously
existed only in a window's own File menu — so the moment it is most useful, a
fresh launch, was the one moment it was missing.

### EDL header

- **Track View is now labelled "Tracks"** — one word, matching SRPs and Marks.
- **Zoom Lock and Play Lock** sit beside the EDL name and the Sample Rate, one
  above the other, sharing a left edge and a width with the rate.
- SRPs, Marks and Tracks sit slightly lower and are a little narrower.
- **A selected clip's border is black and thinner**, not red. Red read as a
  warning on every ordinary selection. The In/Out-override border keeps its
  own colour, since that one does mean something different.

[Back to the list of versions](#versions)

---

<a name="v1-1-47"></a>
## 1.1.47 — 2026-08-28

A follow-up to 1.1.46's sample-rate work: one readout instead of two, a rate that says what it means, and a crash on closing a project.

### Fixed: crash on closing a project

1.1.46 added the EDL sample-rate button and attached the header's shared
button styling to it, but never detached it again on the way out — so closing
a project tore the button down still pointing at styling that had already been
destroyed. That is a hard crash, and it is fixed.

### One sample rate readout, not two

**The Project sample rate button is gone.** The Project takes its rate from
the first file opened in an EDL, and every EDL already shows exactly that, so
a second button above Objects was reporting the same fact in a second place.
The EDL's own readout is the one that stays correct.

It now sits level with the collapse triangle, at the same height as the other
buttons in that row.

### The rate looks settled when it is settled

**Red while locked.** Greying it out said "not available yet", which is the
opposite of what a settled rate means — it is not missing, it is decided. Red
says so, and the tooltip explains: *Sample Rate has been set and can not
change after files have been added.*

**"Sample Rate" on a new Project**, instead of a row of dashes that read as a
value which failed to load.

**Fixed: the readout was not redrawn after opening an EDL.** The rate and the
lock were both decided during the load and neither was reported, so the button
kept the text, tint and tooltip it started with — a locked rate whose tooltip
still claimed nothing had settled it.

**An EDL locks when it has files *and* a rate** — both. Files are what make a
rate unchangeable: they were read at it, and moving it underneath them would
play them at the wrong speed. An EDL saved with a rate but no clips reopens
unlocked and can still be changed.

### A rate you picked before adding files is no longer overwritten silently

Setting the rate on an empty EDL deliberately leaves it unlocked — the first
file is what settles it. But "unlocked" was being read as "unset", so the
first file quietly replaced a rate you had gone to the menu to choose.

Now, when the first file disagrees with the rate you picked, soundBlade asks:
**Change Rate** to take the file's, **Enable SRC** to convert the file to
yours, or **Cancel** to abandon the add. The audio device is then offered
whichever rate the EDL actually settled on.

[Back to the list of versions](#versions)

---

<a name="v1-1-46"></a>
## 1.1.46 — 2026-08-28

Everything since 1.1.42. Releases 1.1.43, 1.1.44 and 1.1.45 went out with 1.1.42's notes inside the DMG by mistake, so this file covers all four.

### Sample rate is now visible, and settles itself

**Every EDL shows its own sample rate**, beside the collapse triangle at the
top of the EDL. **The Project shows its rate too**, above the Objects button
to the right of the time display.

Both follow the same rule: **the rate is taken from the first file opened**.
Before that it is unsettled, and clicking the button lists the rates your
audio device supports so you can choose one. Once a file has settled it, the
button greys out — the rate is decided, and changing it underneath clips that
were recorded at another rate is not something to offer casually.

**Fixed: an EDL saved without a rate could never recover one.** Nothing
re-derived it, and only *adding* a file set it — which an already-populated
EDL never does, so it stayed blank forever while being full of audio that
plainly knew its own rate. Such an EDL now takes its rate from the first clip
that carries one. This affects any EDL saved before the rate was stored at
all.

### Dither: Off / On / Auto, and Auto adds nothing

Dither exists for requantisation — it decorrelates the error made when a
full-precision sample is forced into fewer bits. If nothing has altered the
samples and they leave at the depth they arrived at, there is nothing to
requantise, and dithering anyway adds noise that was not there.

**Auto is the new default** (Project Settings → Delivery), for monitoring and
export alike. Play or print a file untouched and it now comes back
bit-identical. Off and On remain for when you want to overrule that.

It errs toward dithering: anything it cannot be sure about counts as
processing, because a missing dither is a delivery fault while a needless one
is inaudible noise.

### Tools → Run Null Test

Pick a file and find out whether the render path changes it at all. It builds
its own single-clip EDL at unity, renders through the real export path with
dither off, subtracts the source, and reports.

It measures latency too: a path that is bit-identical but *delayed* is
reported as "transparent, but late" with the sample count, rather than as a
flat failure. The report names the first differing sample and the peak
difference and explains how to read them — together those two identify which
stage moved the bits.

### Editing

**The Edit Point.** Clicking in a track places an Edit Point — a vertical line
with a yellow triangle — rather than moving the playhead, so you can mark a
spot while the transport keeps running. When stopped, a click still moves the
playhead as before. It shows across the whole Edit Group.

**Snap to Zone.** Dragging a segment near another's tail snaps it: **blue**
for flush (butted, no gap) and **red** for auto-spaced (your AutoSpacing
Duration between them). Both are offered at once, so where you let go decides
which. Enable it in Application Settings → Editing Tools. With Edit > Delete
Selection this is the quick way to segment, space and resequence a long
continuous mix.

**Fade Tool.** A new preference leaves fade editing armed without holding
Command+Option+Control. That chord is now a momentary toggle of it — it arms
the tool when the preference is off, and *disarms* it while the preference is
on, so you can get past a fade without turning the preference off and back on.

**Cross-lane drag needs no modifier**: drag a clip by its Drag Bar to move it
to another track.

**Fades** regain their full context menu: five curve shapes, five explicit
"Set Fade to Default…" items, and conversion both ways between a fade and a
cross-fade.

**Editing commands need a real selection.** Cut, Copy, Delete, Export
Selection and the rest stay greyed out on an Edit Point alone.

### NoNoise menu

DeClick, DeKrackle and Click Detect now live in one top-level **NoNoise**
menu, and all thirteen are proper commands with keyboard shortcuts and
consistent enabling. Type A, DeKrackle, Detect Clicks, Next/Previous Click,
Process Clicks and Clear Click Detect were previously reachable only by
right-clicking a lane. **Show Interpolations** hides or shows the DeClick and
Click Detect markers.

### Layout tab

A new left-panel tab showing every track of the selected EDL as one row: ADM
channel, number, name, Edit Group, output, mute, solo and a level meter.
Rename, regroup or re-route from there; the output column opens the same menu
the track header does.

**Option-click a group's colour** for a palette grid. Picking a colour another
group holds swaps the two, so no two groups can ever share one.

**Edit Groups now run A–P and a–p** — thirty-two in all. The lowercase bank
has its own colour register so the two are told apart at a glance.

### Object View

Each object is now a **shaded sphere that meters**, filling outward from its
centre through green, yellow and red as its track plays, at the same
thresholds every other meter uses. **Speakers are labelled wireframe boxes**
drawn in blue with real perspective, with a **Show Speaker Labels** checkbox
for crowded layouts.

**Fixed: the Object View was given its speaker layout only once**, when the
window was first created — so a layout chosen or changed afterwards never
reached it, and a window opened before any layout was set showed an empty room
for the rest of the session.

### Open Recent

**File → Open Recent** and the EDLs pane both carry three lists: Projects,
EDLs and media files. In the pane a single click acts — a Project opens, an
EDL joins the current Project at the end, a media file becomes a clip on the
selected track — and media rows drag straight onto a track. Sections fold, and
the lists stay in step across every open window.

### Fixes and smaller changes

- **Local files are no longer read from disk on the audio thread.** Remote
  clips already went through a read-ahead buffer; local ones did not, which
  risked dropouts on a cold cache or a slow disk.
- **All meters now fall at the same rate.** Three of them were using two
  different decay laws, so the same signal decayed visibly differently
  depending on where you looked at it.
- **Plug-ins have one right-click menu**, wherever they sit. A Desk plug-in
  slot gains Open and Change Plug-in, which it could always do but never
  offered. It says **Bypass** rather than "Mute" — a muted plug-in would still
  be in the chain contributing latency and tail.
- **Ctrl-click Mute or Solo** applies it to every selected track; Option-click
  still takes the Edit Group.
- **Ctrl-click a track's output selector** to fan incrementing outputs across
  the selected tracks; **Shift-click** gives the whole Edit Group the same
  choice, panner included.
- **Command+D answers "Don't Save"** on both save prompts.
- **Window positions are remembered** for the Loudness Meter, Object Panner
  and Video windows, and restored on the display they were closed on.
- **5.1.2** joins the speaker layouts, for monitoring and for playback of
  7.1.4 material folded down to it.
- **Loudness metadata** is now both read and written: BWF `bext` version 2
  fields, and a declaration carried in an ADM.

[Back to the list of versions](#versions)

---

<a name="v1-1-42"></a>
## 1.1.42 — 2026-08-26

Two correctness fixes.

#### BWF metadata is now written where the spec says

Exported Broadcast Wave files had their `bext` chunk written at the wrong
byte offsets: **Time Reference**, **Coding History** and the version field
were each two bytes late. Reading our own files back hid this completely —
the same offset error applied in both directions, so they round-tripped
correctly inside soundBlade. Any other application reading them per spec
saw a garbage Time Reference and a shifted Coding History.

Time Reference is the sample-accurate origin timecode of a broadcast wave,
so on a deliverable this is the field that matters most. It is now written
exactly per EBU Tech 3285.

**If you exported BWF files from 1.1.40 or 1.1.41 and their metadata needs
to be correct in another application, re-export them.** The audio in those
files is unaffected — only the metadata chunk was mislaid.

#### A plug-in with latency now starts at the right time

A Desk Event whose plug-in reports latency applied its effect slightly
early — about 43 ms early for a typical linear-phase or oversampling
plug-in at 48 kHz. The effect now begins exactly at the event's start.

Together with the fixes in 1.1.40, entering and leaving a Desk Event
carrying a latent plug-in should now be clean: no dropout, no repeated
audio, and the effect landing where the event actually is.

[Back to the list of versions](#versions)

---

<a name="v1-1-41"></a>
## 1.1.41 — 2026-08-26

Tester-reported fixes.

#### Fades now require Command+Option+Control to edit

Fades sit on top of clips and were easy to grab by accident — every fade
gesture used to be available with no modifier at all, so a stray click near
one could silently reshape it. Editing a fade or cross-fade now takes the
same chord legacy soundBlade required.

With the chord not held, a click near a fade behaves as if the fade weren't
there (time selection, clip drag), rather than being swallowed. The pointer
only shows a fade cursor when the gesture is actually available.

Double-clicking a fade still opens Edit Fade Mode with no modifier —
opening the editor changes nothing on its own.

#### Edit Fade Mode

- **A turned-off fade no longer changes.** The Duration +/− buttons stayed
  live on a disabled fade, so it could still be stepped and the panel would
  redraw showing the change. Those buttons now disable with the rest of
  their side, and every parameter — Duration, Overlap, Power, Alpha, Gain,
  Curve — refuses edits to a disabled side no matter how the edit is
  reached.
- **Fades now carry to the Edit Group on close.** The timeline's own fade
  drag already did this; the EFM panel didn't. It now uses the same
  matching, so both behave identically.
- **Command+F** opens Edit Fade Mode.

#### Placing files

- **Shift-drop now lands a BWF at its real timestamp.** It was reading the
  Time Reference field through a parsing bug that returns a silently wrong
  number on macOS, so files landed at a nonsense position instead of their
  timestamp.
- **Dropping several files** now offers a third placement: **At
  Timestamps** — one file per track, each at its own embedded timestamp,
  alongside the existing "One Track" (sequential) and "New Track Each" (all
  at the drop point). Offered only when at least one file actually carries
  a timestamp; files without one fall back to the drop point.

#### Selection and navigation

- **Command+Option while making a time selection** zooms to that selection
  when you release.
- **Clicking a track or the Desk Events lane** moves the playhead there
  when the transport is stopped.

#### Note on waveforms

Waveform data is cached beside each audio file as `<name>.data` (or
`<name>.chN.data` per channel); Artist Connection files cache under
`~/Library/soundBlade/ArtistConnectionWaveforms/`. These are reused between
sessions — a rescan happens only if the audio file's size or modification
date changed, or if the **Waveform Detail** setting was changed, which
invalidates every cached waveform at once.

[Back to the list of versions](#versions)

---

<a name="v1-1-40"></a>
## 1.1.40 — 2026-08-25

#### New: Export Sound File…

A new command in **File > Export…**, and on the right-click Export submenu
for a time or clip selection. It renders the current selection the way
Export Selection does, but exposes everything the legacy soundBlade HD
command did:

- **Path / Name**, with **Hide Ext** (sets the Finder's own hide-extension
  flag; the file on disk keeps its real name).
- **Bit Depth** — 16 or 24-bit PCM, or 32-bit float.
- **Type** — Interleaved (one combined file) or Mono (one file per channel).
- **Multiple Export** — 48/24, 44/24 and 44/16 rendered in one pass, each
  into its own `48-24` / `44-24` / `44-16` subfolder, independent of the
  project's own rate.
- **Edit after Export** — replaces the exported range back in the EDL, in
  sync. Works for either Type; reinsertion always keeps each track at its
  own native width, so a stereo track stays stereo.
- **BWF metadata** — Originator (defaults to "Sonic Studio soundBlade 3.0",
  Clear empties it), Reference, Date, Time, Description, Coding History
  (auto-filled from the chosen format, and freely editable), and an
  optional ISRC.

BWF/WAV only. Artwork and artist are not settable here — those follow the
source folder and the studio's own defaults.

#### Sonic HD SRC replaces the previous sample-rate conversion

All sample-rate conversion — playback of clips whose file rate differs from
the project, and every export path including Multiple Export — now runs
through the Sonic HD SRC engine (multi-stage polyphase FIR with precomputed
filter tables) instead of the interpolator used before.

#### Fixed: dropouts around plug-ins that report latency

Three separate faults, all heard as a dropout or glitch:

- Entering a Desk Event whose plug-in reports latency dropped out. The
  plug-in's pipeline started empty at the span edge, so its first samples
  were silence. It is now pre-rolled by its own latency so it is primed
  before the span begins.
- Such a track was also out of position by that latency while *outside* the
  span, so the plug-in engaging stepped the audio. Each slot now delays its
  dry path by the same amount, making the span edge seamless.
- A latency-reporting plug-in going live caused a brief silence on other
  tracks, from delay compensation engaging against buffers that had never
  been written.

No audio is altered to achieve this — no crossfades, no resampling of the
dry signal.

#### Artist Connection: Albums and Projects

- **Create Album…** and **Create Project…** in the Library tab, built from
  whatever folders and files are selected.
- A new **Projects** tab listing what this app has created, with per-row
  Refresh and Copy Links. Share links are clickable and copyable.
- Note this lists only projects created *here* — the API has no call to
  list a studio's existing albums or projects, and none to delete them.

#### Smaller changes

- Clicking a track or the Desk Events lane now moves the playhead there
  when the transport is stopped.
- Tooltips on the Project Settings **Production Type** and **Waveform
  Detail** controls.
- Right-click menus in the Studio Browser open next to the pointer.

[Back to the list of versions](#versions)

---

<a name="v1-1-34"></a>
## 1.1.34 — 2026-08-23

#### New: Manual Per-Track Panning

Every track now has a panner button (previously only appeared once a track
already had ADM-authored spatial data). Click it to pan a track's signal
into whatever Monitor Layout is active:

- **Stereo layout** — a small L/R slider.
- **5.1 and wider** — the existing full spatial Object Panner (plan view +
  elevation).

Both write the same underlying pan data, so a track panned in Stereo picks
up correctly if you later switch to a wider Monitor Layout and open the
full panner on it. Bypass it back to fixed-channel routing the same way as
before (Output routing menu > "Object (panned)").

#### Binaural HRTF Presets

Replaced the temporary placeholder HRTF with 5 real presets from the
University of York's SADIE II database: KU100 and KEMAR dummy heads, plus
3 individual human measurements — individualized HRTFs sounded noticeably
better in testing, so several are offered to increase the odds of finding
one close to your own head/ear anatomy.

#### Fixed

- **Plugin editor hang.** Opening a plugin's editor window could hang the
  whole app even for a plugin that had already passed the existing
  instantiation safety check — some plugins' licensing/hardware checks
  only run when their GUI first builds, in a separate resource bundle from
  the one already being tested. That check now happens too, in the same
  disposable background process, before the real editor ever opens.
- **New tracks all defaulting to the same output channel.** New tracks now
  auto-increment their output channel (wrapping around the current Speaker
  Layout) instead of every track landing on "L".
- **Track output label wasn't clickable.** The speaker/channel label in
  each track header now opens the output routing menu directly.

---

#### Also in this release

Everything from 1.1.33 (SOFA HRTF binaural monitoring, realtime plugin
delay compensation, Artist Connection background uploads) and everything
before it.

[Back to the list of versions](#versions)

---

<a name="v1-1-33"></a>
## 1.1.33 — 2026-08-23

#### New: Binaural HRTF Monitoring

**Project Settings > Speakers > Binaural** — monitor a multichannel mix
(5.1, 7.1, 7.1.4, etc.) through headphones using a real SOFA-format HRTF,
instead of the ordinary stereo downmix. Convolves each speaker's signal
against its own direction in the loaded HRTF, so a surround mix actually
localizes in headphones rather than just folding down to stereo.

- **Enable Binaural Monitoring** toggle, a bundled default HRTF to start
  from, and **Load Custom SOFA File...** for your own measurement.
- Global setting (like Dither) — it follows your headphones, not the
  project, so opening a colleague's EDL never silently inherits their HRTF
  choice.
- LFE is folded into both ears rather than dropped.

#### New: Realtime Plugin Delay Compensation

Tracks and the Master Bus insert chain with different plugin latencies
(a lookahead limiter vs. a zero-latency EQ, say) now stay sample-aligned
while monitoring, matching what export already guaranteed. Previously,
only the offline export path compensated for hosted-plugin latency —
realtime playback could drift a heavier track out of sync with a lighter
one, audible during monitoring even though the eventual bounce came out
correctly aligned.

#### Artist Connection

**Library uploads now run in the background** with a per-file queue —
pause, resume, or cancel any upload independently — replacing the old
modal progress window that blocked the tab while uploading.

#### Also

**Send Report** now reaches the current support inbox.

---

#### Also in this release

Everything from 1.1.32 (waveform sidecar read buffering + dedup) and
everything before it.

[Back to the list of versions](#versions)

---

<a name="v1-1-32"></a>
## 1.1.32 — 2026-08-22

#### Fixed

- **Crash on launch** with a Master Bus plugin and a non-stereo speaker
  layout (5.1, 7.1, 7.1.4…) — a startup deadlock in plugin instantiation.
- **Crash on quit** if Edit Fade Mode was left open — closing every EDL
  explicitly before quitting now avoids a dangling reference the old
  shutdown order could hit.
- **Slow project open.** Reopening a project re-read every clip's cached
  waveform data inefficiently — unbuffered, and once per clip even when
  several clips share the same source file. Projects with many clips (or
  several segments cut from one long recording) should open noticeably
  faster now.

---

#### The Track Header

**Gain fader and level meter are now one combined control**, matching the
Desk window's own fader/meter look — the level meter sits embedded in the
centre of the fader (black background), rather than as a separate strip
beside it. The header is about 30px narrower as a result.

**Shift-click the +/− gain buttons for a 10× step** (1.0dB instead of
0.1dB).

---

#### Segment Gain

**Rebuilt Segment Gain dialog** (Edit > Segment Gain…, or Ctrl-click a
clip's Title Bar) — matches the original SonicStudio HD dialog:

- **Absolute / Relative / Normalize** modes, with coarse (1.0dB) and fine
  (0.1dB) step arrows.
- **Normalize** scans the selected clip(s)' true peak level and offers the
  gain needed to bring the loudest one right up to full scale.
- **Reverse Polarity** checkbox, available when a single segment is
  selected.

**Clips with inverted polarity now show a small red dot** in the upper-left
corner of their Title Bar.

---

#### Waveforms

**New EDL > Rebuild Waveforms** — forces every clip in the current EDL to
rescan its waveform from the source audio, rather than trusting whatever's
cached.

**New Waveform Detail preference** (Project Settings > General): Low /
Standard / High / Maximum, trading cache size for on-screen detail when
zoomed in close. Existing waveforms rebuild automatically when you change
it.

---

#### Edit Fade Mode

**"Edit Fade…" is now "Edit Fade Mode"**, and works for any selected clip
that carries a fade — not only right after clicking the fade handle itself.
Also now offered from the right-click menu over a fade.

---

#### Also in this release

Everything from 1.1.31 (the Desk's layout-width Master Bus plugin chain,
Edit Group gestures, Project window resizing) and everything before it.

[Back to the list of versions](#versions)

---

<a name="v1-1-31"></a>
## 1.1.31 — 2026-08-22

#### The Desk

**Master Bus plugins now match the monitor layout.** The Desk has one plugin
chain, as wide as the monitor layout — stereo, 5.1, 7.1, 7.1.4 and so on —
instead of one mono chain per channel. Change the layout and the chain
re-creates itself at the new width (any open plugin editors close first), and
the Desk column and its label follow the layout. When the Desk is in its own
window, the window re-fits to the new width too.

**Single click a Desk plugin slot to open its editor, click again to close.**

**Multiple plugin editors can be open at once** — both Desk plugins and
track plugins. Opening one no longer closes the others.

**Desk meters** show a centred level bar that starts green.

---

#### Editing

**Edit Groups now carry more gestures across the group:** plain-clicking a
clip selects the matching clip on every track in its Edit Group (any clip
that overlaps), a time selection spans the whole group, and Create CrossFade
splits every track in the group at the playhead and selects both halves on
all of them.

**Create CrossFade** is now **Ctrl+G**, and is enabled whenever the playhead
is over a clip on the selected track's Edit Group.

**Adding or dropping a file selects the new clip.**

**Clicking elsewhere during playback no longer stops playback.**

**Up / Down arrows zoom** in and out (no modifier needed).

---

#### Project & window

**New EDLs are named "EDL One", "EDL Two", …**

**File > Reset Default Project** returns New Project to the built-in default:
one EDL, four Small-height tracks, tracks 1–2 and 3–4 in two Edit Groups.

**The Project window fits the tracks** as they resize, and can be resized
shorter with a scrollbar; track lanes are a lighter grey, and the time-
selection border is thinner.

Layout buttons (Monitor Layout / Source Layout) now have tooltips explaining
the difference.

---

#### Fixed

- Crash closing a project with a Desk plugin editor open.
- Crash / hang around opening Desk plugins after a project open.
- Header buttons no longer overlap after resizing.

---

#### Also in this release

Everything from 1.1.30 (Edit Fade Mode: vertical lanes, working Parameter
slider, Prev/Next fix) and the loudness/film-TV measurement work before it.

[Back to the list of versions](#versions)

---

<a name="v1-1-30"></a>
## 1.1.30 — 2026-08-17

#### Edit Fade Mode

**The three lanes now stack vertically**, matching the classic soundBlade
window: the crossfade Result on top, the outgoing clip's lane with its
fade-out curve below it, and the incoming clip's lane with its fade-in at
the bottom — with the parameter table (Duration / % Overlap / dB Down /
Alpha / Gain, one row for Out and one for In) beneath them.

**The Parameter slider now works immediately.** It drives whichever
parameter field is selected (click any field to select it — the classic
one-slider-for-everything design); a fresh session now opens with Duration
already selected instead of an inert slider, and the slider explains itself
on hover.

**Fixed: crashing when stepping between fades with Prev / Next.**

---

#### DDP

**Fixed: a stereo file on a Destination track bled its second channel into
the other side's audio** in the exported image. Each clip is now confined to
its own track's channels.

**Export DDP Image warns when Destination audio is not mono**: a CD image
carries one channel per Destination track, so only each track's first
channel is used — the dialog says so and offers "Use First Channel &
Export" or Cancel.

---

#### Also in this release

Everything from 1.1.29 — layout tooltips, ADM import setting Source Layout
from the file, and the loudness measurement improvements.

[Back to the list of versions](#versions)

---

<a name="v1-1-29"></a>
## 1.1.29 — 2026-08-12

#### The two layout buttons, explained where you need it

**Tooltips on Monitor Layout and Source Layout.** The two buttons answer
different questions and are easy to confuse: Monitor Layout is *the room* —
the speakers you are listening through, bound to your audio device, driving
panning and monitoring. Source Layout is *the mix* — what the content is
authored as, independent of hardware, driving Mixdown and loudness
measurement. Hover either button and it tells you.

**Importing an ADM sets Source Layout from the file.** The file knows what
it is: its bed channel count names the authored layout, so a 7.1.2-bed
Atmos master imports with Source Layout already set to 7.1.2, a 5.1 ADM to
5.1 — and loudness measurement follows the content no matter what machine
you open it on. If the bed matches no named layout (or the file is
objects-only), the setting is left alone, and Auto's routing inference
covers it.

---

#### Also in this release

Everything from 1.1.28 — loudness scans at the content's own sample rate,
and the smarter layout fallback.

[Back to the list of versions](#versions)

---

<a name="v1-1-28"></a>
## 1.1.28 — 2026-08-11

#### Loudness measurement follows the content, not the machine

**Measure Loudness now renders at the source files' own sample rate.** The
EDL's stored rate follows the audio device (it is rewritten on every save
with whatever the hardware was running at), so a 48 kHz ADM master could be
measured at 44.1 kHz just because of where the laptop's output happened to
be. The scans — Measure Loudness, and the measurement Export ADM stamps into
loudnessMetadata — now use the dominant rate of the actual source files, and
the report header says which kind of rate it measured at:

    Sample rate: 48000 Hz (from source files)

Export EDL is unchanged: files are still written at the rate they always
were.

**Smarter layout fallback.** When the EDL has no authored Source Layout, the
scan now takes the *wider* of the monitor layout and what the tracks' own
routing implies — so an immersive session measured on a 2-output laptop can
no longer be mislabeled as Stereo by the device downgrade. An explicitly set
Source Layout is always honored as before.

---

#### Also in this release

Everything from 1.1.27 — the Film & TV loudness presets, dialogue-gated
measurement, and the ADM offline-render fix.

[Back to the list of versions](#versions)

---

<a name="v1-1-27"></a>
## 1.1.27 — 2026-08-11

#### Film & TV loudness

The loudness system introduced in 1.1.25 now speaks film and television
delivery, not just music:

**Delivery presets carry the whole spec.** Each preset in the Loudness Meter
knows its target, its tolerance window, and — crucially — *which measurement
it is defined against*: Dolby Atmos Music and the Netflix family judge the
**5.1 re-render**, while **EBU R128 Immersive** judges the **native
measurement** (BS.1770-4 over all channels of the immersive mix). The meter
and the report read **IN SPEC / LOW / HIGH** — a too-quiet delivery fails QC
just as surely as a hot one, so it is flagged too.

**Film & TV production type.** Project Settings > General now has a
Production Type selector. In Film & TV mode, the EDL menu gains **Set
Selected Tracks as Dialogue**: tagged tracks (marked with a DIAL badge) act
as the gate for **dialogue-gated loudness** — the report's new **DlgInt**
column measures the full mix during dialogue only, which is the number
Netflix-family specs (−27 LKFS ±2, dialogue-gated) are written against, and
the new **NFLX** verdict judges it. The tag never changes playback or
exports; it only tells the measurement where the dialogue is.

**The stereo deliverable is measured too.** Measure Loudness adds a **2.0
fold** table (BS.775 from 5.1), since most specs also bound the stereo
version.

**Measurement follows the mix, not the machine.** The offline scan now
measures against the EDL's authored **Source Layout** rather than the
monitor layout, which auto-downgrades to fit the current audio device — a
7.1.4 master measured on a laptop no longer reads as Stereo once its Source
Layout is set.

The most recent Loudness Report can be brought back to front from the
**Windows menu**.

---

#### Fixed

**ADM offline renders were summing every channel of the master into every
object track.** An ADM object clip plays a single channel of the
multichannel master; the offline renderer ignored that and rendered the
whole master into each object's track — so Export EDL, Export Selection and
Measure Loudness on ADM sessions produced audio that was massively
duplicated, absurdly hot, and slow to render. Renders of ADM sessions are
now correct, several times faster, and far lighter on memory.

The Loudness Meter window could crash on opening. Fixed.

---

#### Also in this release

Everything from 1.1.26, including the rebuilt Artist Connection integration
against the real Partner and Admin APIs.

[Back to the list of versions](#versions)

---

<a name="v1-1-26"></a>
## 1.1.26 — 2026-08-11

#### Artist Connection

The Artist Connection integration has been rebuilt against the **real Partner
and Admin APIs**, replacing the demo API used until now.

**Signing in is now a browser consent flow.** soundBlade no longer asks for a
username and password of its own — you approve access in your browser and
return to the app. That means your credentials are never typed into, handled
by, or stored by soundBlade.

Both halves of the service are covered: the **Partner API** for the listener
catalogue, and the **Admin API** for the studio media library.

---

#### Also in this release

Everything from 1.1.22 through 1.1.25, if you are updating from 1.1.21 or
earlier — including loudness measurement for ADM and immersive mixes, the
Object View, Track View, clip gain, and the large-ADM open performance work.
See those versions' own notes for detail.

---

#### Known limitations

Waveform sidecars are written only when a scan finishes, so quitting part-way
through a large ADM's first scan means it starts again next time.

Build Waveforms is not yet in the clip contextual menu.


### 1.1.24

**1.1.23 could put a constant DC offset on one output channel.** This release
removes it. If you are running 1.1.23, update now.

It was not audible — DC has nothing for a speaker to reproduce — but it sat near
full scale, showed on converter meters, and was present the whole time soundBlade
was running, whether or not anything was playing. Muting that channel at the
converter produced a click.

The cause was the change 1.1.23 made to fix the transport click. Monitoring
dither defaults to a **noise-shaped** type, which carries feedback state per
channel. 1.1.23 began running it on silent blocks as well as playing ones, so
from launch it was fed an unbroken run of digital silence and settled into a
stuck constant.

That change has been reversed. Idle output is true digital silence again.

**If you ran 1.1.23, nothing you exported is affected** — this only ever touched
the monitoring path, never the deliverable. Export dither is a separate setting
and was not involved.

---

#### The start/stop click is back, for now

Reversing the above brings back the small click when starting and stopping the
transport, which 1.1.23 had fixed. That is a deliberate trade: a click is a
nuisance, DC on an output is not.

The diagnosis still holds and the proper fix is coming. Dither is added after the
transport ramp — it has to be, since quantising must be the last thing to touch
the samples — so the ramp cannot cover it, and switching it on and off at the
transport edges steps the noise floor.

The next attempt will bound it explicitly: dither for a set time past a stop,
ramp that tail away, then stop entirely — so the shaper is never fed sustained
silence and idle output is silent by construction.

**Turning Dither → Enable on Output off still removes the click**, if it bothers
you more than the dither does.

[Back to the list of versions](#versions)

---

<a name="v1-1-24"></a>
## 1.1.24 — 2026-08-09

#### Please update from 1.1.23

**1.1.23 could put a constant DC offset on one output channel.** This release
removes it. If you are running 1.1.23, update now.

It was not audible — DC has nothing for a speaker to reproduce — but it sat near
full scale, showed on converter meters, and was present the whole time soundBlade
was running, whether or not anything was playing. Muting that channel at the
converter produced a click.

The cause was the change 1.1.23 made to fix the transport click. Monitoring
dither defaults to a **noise-shaped** type, which carries feedback state per
channel. 1.1.23 began running it on silent blocks as well as playing ones, so
from launch it was fed an unbroken run of digital silence and settled into a
stuck constant.

That change has been reversed. Idle output is true digital silence again.

**If you ran 1.1.23, nothing you exported is affected** — this only ever touched
the monitoring path, never the deliverable. Export dither is a separate setting
and was not involved.

---

#### The start/stop click is back, for now

Reversing the above brings back the small click when starting and stopping the
transport, which 1.1.23 had fixed. That is a deliberate trade: a click is a
nuisance, DC on an output is not.

The diagnosis still holds and the proper fix is coming. Dither is added after the
transport ramp — it has to be, since quantising must be the last thing to touch
the samples — so the ramp cannot cover it, and switching it on and off at the
transport edges steps the noise floor.

The next attempt will bound it explicitly: dither for a set time past a stop,
ramp that tail away, then stop entirely — so the shaper is never fed sustained
silence and idle output is silent by construction.

**Turning Dither → Enable on Output off still removes the click**, if it bothers
you more than the dither does.

[Back to the list of versions](#versions)

---

<a name="v1-1-23"></a>
## 1.1.23 — 2026-08-09

#### No more click on start and stop

Starting and stopping the transport made a small click — even over a silent
stretch of the timeline, where there was nothing playing to click.

The transport ramps were not at fault. Dither is added to what you hear as the
very last step, after those ramps — it has to be, because quantising is the last
thing that may touch the samples. But it was only being added while the
transport was rolling, so the noise floor appeared the instant you pressed Play
and disappeared the instant playback stopped. That step at each end was the
click, and over silence the dither was the only thing there to hear.

Dither now continues across the transport edges and settles out on its own
terms, using the **Turn-Off Delay** already in Project Settings. The floor stays
put where it used to jump.

Nothing to change: this applies whenever **Dither → Enable on Output** is on,
which is the default.

---

#### Please check this one and report back

This release changes when dither is present on the output, so it is worth a look
on real hardware before anyone relies on it.

**With the transport stopped, does your converter show any level at all?**

Stop playback, leave soundBlade sitting idle for a few seconds, and watch the
output meters on your D/A or interface. After the Turn-Off Delay (Project
Settings → Dither, 100 ms by default) they should fall to nothing and stay
there — the output should be true digital silence.

If a level stays parked on the meter, or the meter holds and only clears when
soundBlade quits, **please report it**, along with:

- the interface or converter, and how soundBlade is routed to it
- whether **Dither → Enable on Output** is on or off
- whether it happens with an empty EDL as well as a loaded one

Turning **Dither → Enable on Output** off is the workaround in the meantime; it
brings back the small start/stop click this release fixes, and nothing else
changes.

[Back to the list of versions](#versions)

---

<a name="v1-1-22"></a>
## 1.1.22 — 2026-08-09

#### Playback no longer needs a trip to Audio I/O first

Opening an EDL and pressing Play did nothing. Going into **Audio I/O**, changing
the sample rate and changing it back made it work — every EDL, every launch.

The sample rate was never the problem. If the audio device saved from your last
session could not be reopened — because it is no longer connected, or is running
at a rate it cannot be asked for — soundBlade carried on with **no audio device
at all** and said nothing about it. The transport ran, the playhead moved, and
there was nowhere for the sound to go. Visiting Audio I/O opened a device for the
first time, which is what actually fixed it.

soundBlade now falls back to the system's default output when the saved device
will not open, and reports it rather than failing silently. Your saved choice is
kept, not thrown away, so an interface that is merely unplugged today comes back
on its own when you plug it in again.

---

#### The window no longer locks up while playing

During playback the whole window became unresponsive, redrawing continuously and
leaving nothing for anything else.

Moving the playhead was repainting every track lane in full — every pixel of
every waveform on screen — many times a second, when all that had actually
changed was a one-pixel line. It now redraws only the two columns the playhead
has moved between.

---

#### Objects are visible in the Object View

The Object View reported the right number of objects and showed an empty room.
Every object was being drawn completely transparent, so only the beds appeared —
and because beds sit still at their speaker positions, nothing seemed to follow
the playhead either.

Objects now draw, move with the playhead, and carry their **Edit Group's colour**,
the same rule the beds already followed, so a room full of dots reads as a mix.
Regrouping a track updates the colour straight away. Muted objects stay visible,
dimmed, and keep moving.

---

#### soundBlade no longer asks about sample rate

The prompts offering to change the audio device's rate — when opening an EDL,
and when importing a file recorded at another rate — are gone, along with the
sample-rate pop-up in the EDL header.

Each of them changed the audio device in the middle of a load or an import,
which is the one moment it cannot afford to be restarted. **The device is yours
to set, in Audio I/O.** soundBlade reads it and leaves it alone.

Nothing is lost by not asking. **Enable SRC** already handles a genuine
mismatch, and a clip being converted still shows its green SRC badge — on the
clip, where it matters, rather than in a dialog.

---

#### Closing a Project asks again, with a real Cancel

Closing a Project with unsaved changes saved them without asking, and the only
way to stop a close once it had started was to back out of the name dialog — an
escape that only existed for a Project that had never been saved.

It now asks **Save / Don't Save / Cancel**, the same three choices closing a
single EDL already offered. Cancel stops the close, and stops a quit.

---

#### Artist Connection no longer asks at launch

The sign-in prompt at startup is gone. Signing in is still there whenever you
want it, from the **Sign In** button in the Artist Connection tab, and if you
are already signed in your library still loads as before.

---

#### Smoother transport position

The playing position was being corrected thirty times a second from a value
sampled a moment earlier, nudging playback fractionally backwards each time.
Removed.

[Back to the list of versions](#versions)

---

<a name="v1-1-21"></a>
## 1.1.21 — 2026-08-08

#### Dialog buttons did the wrong thing

Four dialogs acted on the **opposite button** to the one you pressed. The most
visible was the prompt at launch offering to set the sample rate: choosing
**Yes** did nothing, while **No** set it.

The same fault affected:

- **Sample Rate Mismatch** — OK did nothing; Cancel changed the device.
- **Enable SRC** — never did anything at all.
- **Record Folder** — Cancel opened the folder chooser; Choose Folder did
  nothing.

All four now act on the button you press.

**Setting the sample rate is also verified.** A device cannot always run the
rate asked of it — a 96 kHz project on hardware that only does 44.1 and 48 will
quietly get 48. soundBlade now re-reads the device afterwards, says so when the
change did not take, and offers sample rate conversion instead, which is the
only other way to hear the material at the right pitch.

---

#### The EDL's sample rate is now visible

A pop-up beside Track View shows the sample rate of the EDL you are working in,
and sets it.

It is drawn in **goldenrod when the EDL and the audio device agree**, and in
**red when they do not** — so a mismatch stays visible for as long as it lasts,
rather than being something you were told about once when the EDL opened.

The device's own rate is listed in the pop-up so the two numbers can be
compared without going into audio settings.

---

#### Track View

A **Track View** pop-up under the SRPs button hides and shows tracks, for
working in a large EDL without scrolling past everything you are not using.

- **Expand All** shows every track.
- **Collapse All** leaves only the EDL name tab.
- **Feature Tracks** shows only the tracks you have featured.
- **Add Selected Tracks to Featured** adds the current track selection.
- **Clear Featured Tracks** starts over.

Every track is also listed by name, ticked when featured, so the set can be
built up directly.

**The featured set is remembered.** Expanding does not forget which tracks you
picked, so going back to Feature Tracks shows the same ones again. The set is
saved with the EDL.

Hidden tracks remain active parts of the EDL in every way — they play, they
export, they stay in their Edit Groups.

---

#### Other changes

**Option-click Mute or Solo** applies to the track's whole Edit Group. A plain
click still acts on the single track.

**New EDLs are named "EDL 1", "EDL 2"** rather than "Untitled".

**Closing a project saves it** instead of asking. It still asks for a name and
location when the project has never been saved; cancelling that leaves the
project open.

**The clip contextual menu** gains Segment Gain, Set Polarity, Reset Polarity,
Reveal Selected Segment Files in Finder, Selection from Selected Segments, and
Selected Tracks to New Edit Group.

---

#### Known limitations

Waveform sidecars are written only when a scan finishes, so quitting part-way
through a large ADM's first scan means it starts again next time.

Build Waveforms is not yet in the clip contextual menu.

[Back to the list of versions](#versions)

---

<a name="v1-1-20"></a>
## 1.1.20 — 2026-08-07

#### Opening a large ADM

A 100-channel ADM took about fifteen minutes to open. Two separate causes,
both fixed.

**Drawing was reading the file.** While a track's peaks were still being
computed, the lane fell back to a path meant for extreme zoom-in and decoded
audio off the disk **inside the repaint**, one read per horizontal pixel, on
every repaint, for every track. Clips whose peaks are not ready now draw as
plain blocks and read nothing. The EDL opens immediately.

**Peaks were computed one channel at a time.** A multichannel WAV is
interleaved, so reading one channel reads every channel's bytes and discards
the rest — and each channel opened its own reader. A 100-channel master was
therefore read a hundred times over: roughly a terabyte of disk traffic for a
10 GB file. The file is now scanned **once**, computing every channel
together, and every channel's cache is written, so later opens load in
milliseconds.

Waveforms fill in progressively while the scan runs, so a track shows as a
block, then grows its waveform in from the left.

**Waveform scanning now runs at background priority** so it yields to
playback, which reads from the same disk.

---

#### Playback no longer reads the disk on the audio thread

Playback read its audio straight off the disk inside the realtime audio
callback, with no buffering. That survived a quiet disk but not a waveform
scan running beside it, which is what the crackling was.

Audio is now read **one block ahead**, on its own thread. The read-ahead sits
between audio and the waveform scan in priority: it has to beat the scan, so
that audio never waits on the disk, while never competing with audio itself.

---

#### Clip gain

Clips have their own **gain**, in decibels, independent of track volume.

- **Edit ▸ Set Clip Gain…** sets it across every selected clip. A selection
  whose clips disagree opens the field empty rather than at 0.00, so
  confirming cannot silently flatten them to unity.
- **Text View's Gain column** edits it directly. It was a placeholder that
  always read 0.00.

It is applied on playback and on export alike, ahead of the track fader, Desk
Events and the master bus.

---

#### Export now prints polarity

**An inverted clip exported upright.** Polarity inversion was applied on
playback but never on export, so a render did not match what was monitored —
and a polarity flip used to null two sources stopped nulling once printed.

Anything exported before this version that relied on a clip's polarity is
affected and worth re-checking.

A second path that loaded clips from an EDL was also dropping polarity, so a
deliberate flip could be lost on reopening.

---

#### Text View

**Editing Start, End or Duration now moves the clip.** The typed value was
read back by a parser fixed to CD frames at 75 fps, while the field itself was
written in whatever timecode format is on display. The two only agreed when
the display happened to be set to CD 75; with it in seconds or samples a typed
time was read as a frame count and the clip went somewhere unrelated.

**Show Text View toggles.** Choosing it again closes the pane. Waveform and
Bar are two ways of drawing the lane, so re-picking one is rightly a no-op —
but Text View opens a pane, and anything that opens a pane needs the same
command to close it.

---

#### Tracks, clips and the EDL list

**Option-click Mute or Solo** applies to the track's whole **Edit Group**. A
plain click still acts on the single track, so checking one channel of a
grouped multichannel take is still possible.

**Bar View and Text View work together.** Text View is a pane below the lane,
not a way of drawing the lane, and it was wrongly grouped with Waveform and
Bar as though the three were alternatives. Bar plus Text is the useful pairing
on a large ADM: instant blocks while waveforms build, with the editable
segment list underneath.

**The clip contextual menu** gains Segment Gain, Set Polarity, Reset Polarity,
Reveal Selected Segment Files in Finder, Selection from Selected Segments, and
Selected Tracks to New Edit Group.

**New EDLs are named "EDL 1", "EDL 2"** rather than "Untitled", which with
several open was the same non-answer repeated.

**Closing a project saves it** instead of asking. It still asks for a name and
location when the project has never been saved; cancelling that leaves the
project open.

---

#### Known limitations

Waveform sidecars are written only when a scan finishes, so quitting part-way
through a large ADM's first scan means it starts again next time.

Build Waveforms is not yet in the clip contextual menu -- it needs a way to
invalidate and requeue a scan, which does not exist yet.

[Back to the list of versions](#versions)

---

<a name="v1-1-19"></a>
## 1.1.19 — 2026-08-07

#### Clicks on start and stop are gone

Starting and stopping the transport clicked. Both ramps are now **10 ms**,
long enough to cover a full cycle around 100 Hz, so there is no discontinuity
left in normal programme material to hear.

The previous value was tied to soundBlade's smallest drawable fade, on the
reasoning that a transport ramp should be no longer than the shortest fade you
can place by hand. That was the wrong comparison. A drawn fade is an edit put
deliberately where you chose; a transport ramp has to kill a click at whatever
sample you happened to hit stop on, which may sit anywhere on a low-frequency
waveform, nowhere near a zero crossing. It needs more room, and now has it.

**Play Lock still starts every locked EDL on the same sample.** The fade-in is
armed at the moment the lock releases, not when Play is pressed, so locked
EDLs ramp through identical gain values on identical samples and still null
against each other.

---

#### Clips are selected by their title bar

Every clip now draws a **title bar** across its top edge — grey normally,
yellow when the clip is selected. It was there before, but only appeared once
a clip was already selected, which made it a handle for moving something you
had picked somewhere else.

**Clicking the title bar selects the clip. Dragging it moves the clip.**

**The clip body no longer selects.** Clicking anywhere in it starts a time
selection. Previously an invisible line halfway down each lane decided which
of the two a click meant, and there was nothing on screen to tell you where
that line was.

The clip's name, its sample-rate-conversion indicator and its **Mute** button
all sit on the title bar, and it is where any further per-clip button will go.

Clip-edge trimming is unchanged, and clicking empty lane space still clears
the selection.

---

#### Text View

Text View is now **its own pane below the track**, the way the plugin panel
is, rather than replacing the waveform. The waveform stays visible. Bar View
is unchanged — it still changes what the lane itself draws and adds no pane.

The list is larger and **editable**:

- **Segment Name** renames the clip.
- **Start** moves it — its length is kept, so End follows.
- **End** and **Duration** trim it — its start is kept.

Edits go through the same undo step a drag or trim on the lane does, so typing
a change and making it with the mouse are one kind of thing to undo. Editing a
segment's Start carries an ADM object's position keyframes with it, exactly as
dragging the clip does.

---

#### Known limitations

The Gain column in Text View is still a placeholder — soundBlade has track
volume and fades, not per-segment gain, so every row reads 0.00.

The Text View pane shows five rows and scrolls beyond that, rather than
growing to fit a track with more segments on it.

[Back to the list of versions](#versions)

---

<a name="v1-1-18"></a>
## 1.1.18 — 2026-08-07

#### Exports now carry your processing

**A DDP export used to be a dry mix.** The programme was rendered straight from
the clips, with none of the plugins you had been listening through — so the
disc did not match the mix.

An exported DDP now prints:

- each programme track's **Desk Events**, applied to that track's own audio
  before the two sides are summed, so each side gets its own processing
  exactly as monitored;
- the **Master Bus inserts** for those channels, applied after the sum;
- **dither**, last of all.

Plugin **automation** is printed too, and **plugin latency is compensated** —
an insert reporting latency no longer prints time-shifted, and its tail is
flushed rather than lost. That matters most where two programme channels carry
different inserts: uncompensated, the two sides would no longer line up with
each other.

A plugin that fails to load is skipped rather than failing the whole export,
and any plug-in already disabled this session stays disabled.

---

#### Dither

A new **Delivery** tab in Project Settings, carrying soundBlade's dither:

**Enable on Output** and **Enable on Export** are separate switches. Dithering
the deliverable is a mastering decision; dithering what you hear is a
monitoring one, and you may well want one without the other.

**Dither Type** — None, Rectangular PDF, Triangular PDF, Noise Shaped, Shaped
PDF.

**Bit Resolution** — 16, 20, 24 or 32-bit PCM, or 32-bit float. Float is not
quantised at all, so dither does nothing there whatever the type says.

**Turn Off Delay** — how long dither keeps running after the signal stops, so
the noise floor does not gate on and off between segments.

Settings are global rather than per-EDL: dither is a property of what you are
delivering, and letting it differ between two EDLs in one Project is a way to
ship an inconsistent master by accident.

Monitoring dither is applied to the master bus as the very last thing before
the audio device, so what you hear is what the deliverable will be.

---

#### The EDL Desk

**The Desk window's plugin stripes now line up with the meters.** They were
drifting five pixels further out with every channel — eighty pixels across a
sixteen-channel layout, which is why nothing sat over its own meter.

---

#### Other changes

**ADM export** prints each object's plugins, while leaving the objects
themselves mono and unpanned — the object paths are untouched. Master Bus
inserts are deliberately not applied to an ADM export for now.

**The Artist Connection tab is hidden** for the time being. Nothing behind it
has been removed.

---

#### Known limitations

The Gain column in Text View is still a placeholder — soundBlade has track
volume and fades, not per-segment gain, so every row reads 0.00.

[Back to the list of versions](#versions)

---

<a name="v1-1-17"></a>
## 1.1.17 — 2026-08-05

#### Large sessions open far faster

Reopening a big session — a 60-track ADM especially — took minutes, and took
just as long the second time even though its waveform caches were already
built. The caches were not the problem: alongside them, a separate thumbnail
was being built for every clip, and building one reads the whole audio file.
On an ADM every channel is a view onto the *same* file, so a 60-channel master
was decoding itself sixty times over, on every single open.

Those thumbnails are only ever drawn while a waveform cache is still being
computed. Where a cache already exists they are no longer built at all.

The first open of new material is unchanged — that is genuinely building the
caches — but every open after it should be dramatically quicker.

---

#### Track Display Type

Each track can now be drawn three ways, from the EDL menu:

**Show Waveforms** (Cmd-Y) — as before.

**Show Bar View** (Cmd-B) — each clip as a plain named block.

**Show Text View** (Opt-Cmd-T) — the track as a list: Segment Name, Start, End,
Duration and Gain, one row per clip.

Bar and Text need no audio data at all, so they are readable the instant a
session opens, before any waveform has been built — which is what makes a large
ADM workable while its caches fill in. The setting is per track and is saved
with the EDL, so a bed you are reading waveforms off and a hundred object
tracks you only need the extents of can be shown differently at the same time.

Selection is shared across all three: a clip picked in one view is highlighted
in the others.

*The Gain column is a placeholder — soundBlade has track volume and fades, not
per-segment gain, so every row currently reads 0.00.*

---

#### ADM import

**An ADM now opens as its own Project**, in its own window, holding that one
EDL. It used to be added alongside whatever was already open, which quietly
merged a hundred-plus track delivery into work in progress.

**Object tracks are no longer grouped.** Everything outside the bed used to
land in one shared Edit Group, so an edit aimed at a single object dragged
every other object with it. The bed keeps its own group.

---

#### Working with several tracks at once

Track height, Track Display Type, Edit Target and **setting an Edit Group** now
all apply to every selected track rather than only the one clicked.

---

#### The EDL Desk

**The Desk pane in the EDL header shows its Solo/Mute buttons again** — they
were being laid out below the visible area of the pane.

**The header is back to its proper height.** It had grown by around 40 pixels,
leaving an empty band beneath the meters.

**The Desk window no longer resizes its contents.** It used to scale the whole
strip to whatever size the window was, which on a narrow channel count blew the
meters up several times over. Meters are drawn at their own size and the window
is sized to fit them — the meters plus a 10 px border, with no scroll bar.

---

#### Fixes

**Opening a Project with cached waveforms could crash.** Introduced during the
speed work above and fixed before release, but worth stating plainly.

**Quitting could crash.** The native menu bar was being unhooked after the
objects behind it had already gone. More likely to have been hit since ADM
import began opening a second window.

**A background waveform scan could outlive the session it belonged to**, which
showed up as a leak warning on quit and was, less visibly, a scan reading
through a reference to something already destroyed.

**Command-clicking a track cleared the other selected tracks.** The gesture
worked in the track header but not on the track itself.

**Play-Locked EDLs could start a block apart** — up to 512 samples, fixed and
never corrected, so a phase-null test between two EDLs would not cancel. They
now start on the same sample.

**Opening a DDP image** now tags its two programme tracks as Destination in one
Edit Group, so a disc opened in soundBlade can be exported straight back out;
previously the export refused it. Tracks also open at the Small height rather
than an out-of-range value.

**Closing a Project with a plugin editor open crashed**, and was the cause of
the leak reported on quit.

[Back to the list of versions](#versions)

---

<a name="v1-1-16"></a>
## 1.1.16 — 2026-08-04

#### CD-Text now reaches the disc

Exporting a DDP wrote the audio, the PQ descriptor and the map, but nothing
carrying the titles and artists typed into the Mark Tab. A set exported from
soundBlade and reopened came back with every track untitled, and a set sent to
a replicator carried no text at all.

Both files are now written.

**TS** is soundBlade's own readable copy of the CD-Text, written on every
export. It is what lets a DDP folder reopen here with its titles intact.

**CDTEXT.BIN** is the packed binary a replicator actually reads, and is what
puts text on a pressed disc. It is written when **Include CD-Text** is ticked
in the Mark Tab — a new checkbox in the PQ OFFSETS header, on by default.
Unticking it exports the same programme with no CD-Text, which is a perfectly
valid DDP; a CDTEXT.BIN left over from an earlier export is removed rather
than left to contradict the box.

Accented titles are handled properly — Portuguese, Spanish and French track
names come through with their accents rather than as stripped ASCII.

Disc-level title and performer are not yet editable anywhere, so they are
written empty.

---

#### The Mark menu generates marks from the edit

Four commands, all working from a selection of segments or a region:

**Segments to Start Marks** places a Start of Track at the beginning of every
selected segment, spaced or butt-spliced.

**Edited Black to Start Marks** places one only where a segment has space
before it — the black an edit left behind, as opposed to silence inside the
audio.

**Edited Black to Start/End Marks** adds an End of Track wherever a segment
runs into space.

**Analog Black to Marks…** measures the audio itself, and places End/Start
pairs where it stays below a chosen level for long enough. Its default
amplitude lives in **Preferences → Editing Tools**.

A whole run lands as one undo step, and a mark is never stacked on a position
that already has one — two marks on a single CD frame cannot be written to a
disc.

---

#### Plugin automation

**Recorded automation was quantised to 33 ms.** Every automation point was
timestamped from the on-screen playhead, which is only refreshed thirty times a
second — so a whole run of parameter moves inside one refresh shared a single
timestamp, and a smooth panner gesture came back as a staircase. Points are now
timestamped from the transport itself.

**Automation is applied more finely.** A parameter used to be set once per audio
block, so the applied value stepped about every 10 ms regardless of how smooth
the recorded curve was — inaudible on a slow fade, audible as zipper on a fast
pan. While automation is moving, the block is now processed in smaller pieces
with the parameter re-set before each. Blocks whose automation is static are
untouched, and cost exactly what they did before.

---

#### The EDL Desk

**The Desk window no longer resizes its contents.** It scaled the whole strip to
fit whatever size the window was, which on a narrow channel count blew the
meters up several times over just to fill the title bar. Meters are drawn at
their own size and the window is sized to fit them — exactly the meters plus a
10 px border, with no scroll bar.

**The EDL header resizes to match.** Handing the strip back from the Desk window
left the meters taller than the row holding them; the header now measures the
strip rather than assuming its height, and gives the room back to the tracks
when the Desk takes it away again.

---

#### Fixes

**Copying clips from several tracks pasted them onto one.** Copying a clip from
each of two tracks and pasting produced both on a single track, one hidden
under the other. Both copy paths now keep the shape of what was copied.

**Command-clicking a track cleared the other selected tracks.** The gesture
worked in the track header but not on the track itself, where a click replaced
the whole selection before the modifier was even looked at.

**Play-Locked EDLs could start a block apart.** They were started one at a time
from the UI thread while audio ran independently, so two EDLs playing "in sync"
could sit 512 samples out — a fixed offset, never corrected, and invisible
unless you went looking. They now start on the same sample, so a phase-null
test between two EDLs cancels as it should.

**Closing a Project with a plugin editor open crashed.** The editor was never
deleted, so the plugin was torn down with its editor still attached. That same
fault was the leak reported on quit.

**A plugin that hangs while loading no longer freezes soundBlade.** Scanning a
plugin means loading it, so a plugin that wedges during startup — a licence
check that never returns, most often — took the whole application with it, and
clearing the plugin list to rescan walked straight back into it. Scanning now
happens in a separate process that can be timed out, and a plugin that hangs is
skipped by later scans instead of hanging each one.

**DDP export no longer renders the whole EDL.** On a large multitrack master it
built an image as wide as every track in the session — minutes of apparent hang
for a result that was not a CD image. It now renders only the two tracks the
disc is actually made from.

[Back to the list of versions](#versions)

---
