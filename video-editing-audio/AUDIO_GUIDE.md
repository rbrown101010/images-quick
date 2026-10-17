# Audio plan for the "Video Editing" video

Checked 17 Oct 2026. Every track here is cleared for a monetized YouTube video. Only the Kevin MacLeod tracks need a credit.

## The short version
- **Music:** one quiet, steady electronic track under the whole video. It should feel modern and techy, have no vocals and no busy melody, and sit at **100 to 120 BPM**. It stays about 18 dB under your voice and swells only in gaps and at the end card.
- **Sound effects:** a whoosh on every camera move between Blender shots, a soft pop for each logo or label, quiet foley (typing, marker, phone tap, robot arm) where the action is on screen, and one riser into a chime for the render reveal. They should be felt more than heard; the script asks for "high quality yet not too dominant sound effects".
- **Files:** edit in **WAV, 48 kHz** to match the video. Export the final as **AAC-LC stereo, 48 kHz, 384 kbps** in the MP4, which is [YouTube's recommended upload setting](https://support.google.com/youtube/answer/1722171?hl=en).
- **Loudness:** master to about **-14 LUFS integrated, true peak no higher than -1 dBTP** ([IRPR mixing guide](https://sounddesign.irpr.agency/guides/how-to-mix-audio-for-youtube/)). YouTube turns louder masters down anyway.

## What's in this folder

### Generated here (made from scratch in code, so no license and no credit needed)
| File | Use |
|---|---|
| `music/music_room-pulse_100bpm.wav` | **First pick.** A soft pulse with pad, arpeggio and light drums. Its sections match the edit: pad-only intro, a breakdown near 1:50, and a fade at the end. About 3:34. |
| `music/music_render-farm_118bpm.wav` | A more driving version for a faster cut. About 3:34. |
| `music/music_whiteboard-calm_84bpm.wav` | A calm electric-piano bed, if the video should feel explanatory rather than hype. About 3:28. |
| `sfx/sfx_whoosh_fast-01/02` | Quick cuts between shots, 0.35 to 0.45 s. |
| `sfx/sfx_whoosh_medium-01/02` | A normal camera move from one Blender shot to the next. |
| `sfx/sfx_whoosh_long-zoom_1.6s` | The "zoom out, move, ease in" move. It has a low swell. |
| `sfx/sfx_whoosh_air-soft_0.6s` | The lightest whoosh, for small pushes and zooms on the computer's "thinking". |
| `sfx/sfx_riser_reveal_2s` and `sfx_riser_short_1s` | The build into a reveal, such as the "Opus 5.5" zoom or the render result. |
| `sfx/sfx_impact_soft-low_1.6s` | Lands the title or the key word. Keep it low in the mix. |
| `sfx/sfx_ui_pop-mid`, `sfx_ui_pop-high`, `sfx_ui_tick` | Logos appearing (Premiere, CapCut, Resolve), scene labels, highlighted words. |
| `sfx/sfx_chime_render-done` | The render finishing on GPUs "in under 12 minutes". |
| `sfx/sfx_glitch_code_0.35s` | Code turning into video, or the "Generating Video" phone screen. |
| `sfx/sfx_servo_arm-move_1.2s` | The robot arm placing table objects. |

### Vetted downloads (run `fetch_licensed_audio.sh` on the MacBook)
This cloud session can't reach these sites directly, so the script downloads them. Every URL was tested on 17 Oct.

**Music: Kevin MacLeod, CC BY 4.0 (credit required)**
| Track | BPM | Feel | Why |
|---|---|---|---|
| Tech Live | 124 | Grooving | He describes it as interview music that "does nothing and goes nowhere", which is exactly what a talking-head bed needs. **Best licensed pick.** |
| Floating Cities | 120 | Calm, futuristic | Spacious and "future", good for the 3D room. |
| Inspired | 120 | Uplifting, corporate tech | Warmer and more emotional; works for the closing CTA. |
| Screen Saver | 120 | Calm groove | Light synth bleeps. |
| Limit 70 | 103 | Relaxed groove | Long (5:02), so it never needs looping. |
| Chill Wave | 100 | Relaxed | Mellow synth bed. |
| Jerry Five | 90 | Driving, relaxed | He says it has "lots of space". |
| Rising Tide | 106 | Mysterious, driving | Darker. Use it if the video leans dramatic. |

**Credit line for the YouTube description** (put it in the description itself, not only on screen; incompetech says a credit placed only in the video is the usual cause of a Content ID claim):
```
Music: "Tech Live" by Kevin MacLeod (incompetech.com)
Licensed under Creative Commons: By Attribution 4.0
https://creativecommons.org/licenses/by/4.0/
```
If a claim still appears, add the credit, then dispute the claim; incompetech says claims are usually released within 72 hours ([incompetech Content ID page](https://incompetech.com/music/royalty-free/youtube-contentid.html)).

**Sound effects: Freesound, all CC0 (public domain, no credit needed)**
| Use | Freesound sound |
|---|---|
| Whoosh | [Swoosh, Shinplaster](https://freesound.org/people/Shinplaster/sounds/264777/), [swoosh, Halgrimm](https://freesound.org/people/Halgrimm/sounds/169867/), [quick woosh, florianreichelt](https://freesound.org/people/florianreichelt/sounds/683101/), [Swing Woosh, Jofae](https://freesound.org/people/Jofae/sounds/389590/) |
| Riser | [Riser short, syntheffects](https://freesound.org/people/syntheffects/sounds/685256/), [impact riser 01, soramoosic](https://freesound.org/people/soramoosic/sounds/244249/) |
| Pop and click | [Plop!, Breviceps](https://freesound.org/people/Breviceps/sounds/447910/), [UI Button Click, benzix2](https://freesound.org/people/benzix2/sounds/467951/) |
| Impact | [Soft Cinematic Impact, Rizzard](https://freesound.org/people/Rizzard/sounds/560156/), [Soft Dramatic Impact, NeoSpica](https://freesound.org/people/NeoSpica/sounds/504614/) |
| Typing | [Keyboard typing, Breviceps](https://freesound.org/people/Breviceps/sounds/447909/), [Keyboard Typing, florianreichelt](https://freesound.org/people/florianreichelt/sounds/448209/) |
| Phone tap | [Scroll and Tap Foley, UnplugTheFridge](https://freesound.org/people/UnplugTheFridge/sounds/531501/), [PhoneTaps, djf54](https://freesound.org/people/djf54/sounds/469297/) |
| Whiteboard marker | [marker on whiteboard, edctrainer](https://freesound.org/people/edctrainer/sounds/251677/), [Writing on whiteboard, giddster](https://freesound.org/people/giddster/sounds/360484/), [whiteboard squeak, Eneasz](https://freesound.org/people/Eneasz/sounds/124758/) |
| Chime | [Achievement Chimes, LaurenPonder](https://freesound.org/people/LaurenPonder/sounds/635665/), [Friendly UI App Jingle, TommasoMotteran](https://freesound.org/people/TommasoMotteran/sounds/858479/) |
| Robot arm | [Servo noises, peridactyloptrix](https://freesound.org/people/peridactyloptrix/sounds/188821/), [MechanicalClamp, Skullsmasha](https://freesound.org/people/Skullsmasha/sounds/123253/) |

## Where each sound goes (follows the script)
| Moment in the script | Sound |
|---|---|
| Cold open: "The latest Claude model is completely taking over video editing" | Music starts low under the line. `riser_short` leads into the zoom on "Opus 5.5" and `impact_soft-low` lands on the model name. |
| 2D / 3D / sound-effect demo | A whoosh on each switch. Let the demo's own sound play and dip the music. |
| Phone shows "Generating Video" | Phone tap, then `glitch_code` very low. |
| Premiere Pro, CapCut and DaVinci Resolve logos next to a video file and code | One `ui_pop` per logo, staggered about 120 ms apart. Use `ui_tick` when the code appears. |
| Stock footage split into labeled scenes | `ui_tick` on each label. |
| Every move between Blender shots (computer, phone, table, whiteboard) | `whoosh_medium` for a normal move, `whoosh_long-zoom` for zoom out, move, ease in, and `whoosh_fast` for quick cuts. Start the whoosh 2 to 4 frames before the move so its peak lands mid-move. |
| Whiteboard: the prompt is written and key words highlighted | Marker foley, very quiet (Ep 1 note: keep the pen sound low). `ui_pop-high` on each highlighted word. |
| Claude Code steps (transcribe, cut, match lines to shots, build screens) | A short typing burst on computer shots and a `ui_tick` per step. |
| Robot arm places objects | `servo_arm-move`, low. |
| Render on rented GPUs "in under 12 minutes" | `riser_reveal`, then `chime_render-done` on the result. |
| Phone goes full-screen TikTok-style clip | `whoosh_air-soft`, and dip the music 3 dB more if the clip has its own audio. |
| CTA: comment "Opus" | `ui_pop` when "Opus" appears on screen. Lift the music 4 to 6 dB after the last word and fade it out over 2 s. |

## Levels (starting points; trust your ears)
- **Voice:** the anchor. Speech should average about -14 LUFS short-term, with peaks around -6 dBFS.
- **Music under the voice:** about 15 to 20 dB below the voice, so roughly -32 to -30 LUFS. Duck it an extra 3 to 6 dB with a sidechain, or let it come up 6 dB in pauses longer than 1 s.
- **Whooshes and transitions:** peaks around -18 to -14 dBFS. They should never mask a word, so if a move lands on speech, use the lighter whoosh.
- **Pops and ticks:** peaks around -22 to -18 dBFS.
- **Foley (typing, marker, phone, servo):** peaks around -30 to -24 dBFS, quieter than you'd expect.
- **Riser, impact and chime:** peaks around -16 to -12 dBFS. These are the only "featured" sounds.
- **Master:** -14 LUFS integrated, true peak no higher than -1 dBTP. With ffmpeg: `loudnorm=I=-14:TP=-1:LRA=11`.

## File and format rules
- Keep all working audio at **48 kHz**. Convert MP3 downloads to WAV before editing (`ffmpeg -i in.mp3 -ar 48000 out.wav`) so nothing is resampled twice.
- Generated files are 48 kHz, 16-bit stereo WAV. Each music track also has an MP3 copy for quick listening; edit with the WAV. Music is normalized to -16 LUFS and SFX to -3 dBFS peak, so turn them **down** in the mix; the levels above are the targets.
- Final export: AAC-LC, stereo, 48 kHz, 384 kbps ([YouTube spec](https://support.google.com/youtube/answer/1722171?hl=en)).
- Instagram, TikTok and Shorts use the same file; they normalize loudness too.

## Other sources, if more music is needed
- **YouTube Audio Library** (YouTube Studio → Audio library): the safest choice for YouTube, and it can filter for "no attribution required". It needs Riley's Studio login, so download from there.
- **Kevin MacLeod / incompetech:** about 1,400 tracks, all CC BY 4.0, filterable by feel and BPM.
- **Freesound with the CC0 filter:** the best free source for sound effects.
- Pixabay Music is also free for YouTube, but it blocks automated downloads; browse it by hand.

## How the generated audio was made
`synth.py` (copied here) builds every generated file from oscillators and filtered noise in NumPy, with no samples. Run `python3 synth.py out_dir music` or `python3 synth.py out_dir sfx` to regenerate. The ElevenLabs connection can't generate sound or music: its API key is missing the `sound_generation` and `music_generation` permissions (tested 17 Oct).
