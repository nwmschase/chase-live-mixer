# Chase Live Mixer

Phone-friendly static live mixer: **backing + vocal stem** (vocal EQ → reverb → gain, mix EQ, mute/solo, Save download).

Backing defaults to `inst.mp3` (full mix minus the Demucs vocal) so the vocal you hear is the processed stem; tap **Original full mix** to play `full.mp3` with the stem layered on top (old behaviour — the mix's own dry vocal masks vocal EQ/reverb).

Open `/` or `/index.html` on GitHub Pages. Tap **Load**, then **Play**.

Defaults: backing 0 dB, vocals −3 dB, mix mids +4, master −3, vocal reverb wet 0.42 / dry 0.70 / room 0.62 / damping 0.22 (Bridge preset).

Sliders: drag sideways (vertical swipes scroll the page), −/+ for fine steps (hold to repeat), ↺ or double-tap to reset. Solo Vocals to verify the stem loaded.

## Egil intro (build 2026-10-08-fx3)

The first 10 s of `stems/egil-final/full.mp3` and `inst.mp3` have been replaced with a lone wolf howl: 0:00–0:10 is the howl, then the song picks up at 0:10 with a 0.3 s equal-power crossfade centred on the 10 s mark. The total length is unchanged (240.000 s) and the timing is sample-exact, so `vocals.mp3` (silent for the first 10 s) is untouched and still lines up.
Howl: "Cooper Creek 20160313_014852 solitary wolf howl very clear.wav" by betchkal, https://freesound.org/people/betchkal/sounds/500646/ — CC0 1.0 (public domain dedication). Used source 0:01.30–0:11.45, high-passed at 70 Hz, about −16 LUFS (the song runs at about −14 LUFS).
