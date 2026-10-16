# How we make a code-drawn video

## 1. The idea
Every frame is drawn by a program as a pure function of time: give it a time in seconds and it paints the whole frame.
A headless browser photographs each frame and ffmpeg encodes the video. Because nothing depends on the frame before,
renders repeat exactly, run in parallel, and resume after a stop.

## 2. The steps
1. **Brief.** Write who the piece is for, the one thing a viewer should remember, the format (vertical 1080 x 1920
   for Reels and Shorts, horizontal 1920 x 1080 for YouTube), the length and the tone.
2. **Facts first.** Put every number, date, name, quote and verse that will appear on screen in one facts file, each
   with its source, the exact quote, the date you checked it, and a named reviewer. The drawing code reads text from
   that file; it never types a number.
3. **Script and voice.** Write short, plain sentences. A real person records the narration; a synthetic voice is only
   a stand-in to time a draft, and it never ships.
4. **Storyboard by beats.** One beat per idea, each tied to the word that cues it. Choose how each thing arrives: a
   building or a card draws itself on, like a pen, rather than fading in.
5. **Build one beat, then look.** Render stills at each beat's cue word and half a second later. Look at them before
   you build the next beat. Never tune a scene to pass a number; tune it until it looks right.
6. **Sound.** Music that is code-composed, public domain, or CC BY with its credit on the end card. Effects follow the
   motion they belong to: when a motion moves, its sound moves with it. Mix to -16 LUFS with the true peak at or
   under -1 dBTP. Offer a version without music, with a softer effects set.
7. **Check and deliver.** Captions match the spoken words exactly (2 to 4 words each, or full sentences when the style
   calls for it). Every on-screen fact matches its source. Text clears the phone's safe zones. Then the owner watches
   the draft, by eye and ear, before the final.

## 3. Drawing that holds up on a phone
- Draw geometric things in code (buildings, charts, maps, documents). Take people, animals and plants from a licensed
  illustration kit or a figure rig; never draw a real person's likeness, and never use AI-generated people.
- Measure a real building from a straight-on photograph; draw domes as round solids seen from below; remove hidden
  lines by erasing what each nearer part covers.
- Make lines heavier than feels right on a desktop: fine lines vanish on a phone.
- Light only the one opening the story points at (a door), not every window.
- Let colour carry meaning, and keep each accent rare.

## 4. Motion that reads as weight
- A figure that lands: a small rise first, an eased descent that slows into the surface, the knees take the weight,
  a settle. No squash, no slam.
- A figure that walks in: arms swing against the legs, the hips shift over the standing leg, the stride fades as he
  arrives, one soft knee dip.
- A collapse into an object matches the object's place, size and moment exactly, so the cut is invisible.
- A white flash hands over to light, never straight back to dark.

## 5. When a real person is on screen
Their footage plays exactly as recorded: full frame, their own captions, nothing of ours on top. Cut into it only after
their own burned-in caption from the previous section has cleared. A name and title appear only while they are on screen.
