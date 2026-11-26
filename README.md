# Nusaybah's Robot Counting

A counting and first-words game for a 3-year-old, starring Robo the robot and friends Pip, Luna and Bolt.

Open `index.html` through a web server (it loads `game.json`, `img/` and `voice/` next to it), tap the big pink Play button and turn the sound on.

## How it plays

- **Tap & count** (most rounds): animals, fruits, food, vehicles, sky things, toys and people appear in their own scene (cats in the living room, fish under the sea, cars on the road). Each tap says the number. At the end Robo says the number and the name ("Six ducks!"), then they leave in their own funny way: ducks waddle, rabbits hop, fish swim, cars zoom, rockets blast off, with a sound to match ("Quack, quack!").
- **How many?**: count, then tap the number. On a wrong answer Robo counts with her, and numbers pop up on each thing.
- **Feed Robo**: "Give Robo three bananas!" Each food she taps flies into Robo's mouth.
- **Presents**: every 2 rounds a present opens a picture of a new Robo adventure: home life (brushing teeth, bath, bedroom, kitchen, fridge), rides (car, plane, train, rocket), pets, outfits, play, and trips to monuments in India and around the world ("I am at the Taj Mahal, in India!"). They never run out and are kept in the photo album (yellow button).
- **Tap Robo** for 12 different reactions: giggles, silly face, dizzy spin, hearts, sneeze, sleepy, dance, peekaboo and more.
- Numbers start at 1–3 and slowly grow to 10. Progress is saved in the browser.

## How it was made

- Pictures: Google Nano Banana models (Gemini image generation). Robo's poses and all adventure pictures use the main Robo design as a reference, so Robo looks the same everywhere.
- Voice: Google Cloud Text-to-Speech, voice `en-US-Chirp3-HD-Leda`, speaking rate 0.85. Lines are packed into one MP3 per group in `voice/`, with start times in `voice/voice.json`.
