# Classroom Memory · Wide

A 16:9 classroom memory game with three rounds and recorded English answers.

1. Press **Play** to remember the picture for 10 seconds.
2. Find three changes and click the changed objects.
3. **Next round** starts the next countdown immediately.

The answers describe the current picture first, then the original picture after **No!**.

Background audio starts with Play, continues between rounds, and stops on reset or finish. Its default volume is **3%**; the musical-note button opens the volume slider. The speaker button controls the recorded answers.

## Run locally

No build or dependencies are required. Keep `index.html`, `assets/` and `audio/` together. In this folder run:

```sh
python -m http.server 8000
```

Then open http://localhost:8000.

## Files

- `index.html`: interface, styles and game logic.
- `assets/classroom-wide.png`: classroom illustration.
- `audio/01-chairs.mp3` through `audio/09-pens.mp3`: recorded answers.
- `audio/background.mp3`: processed background recording.
- `audio/cues.json`: answer text and audio mapping.
- `audio/background-processing.json`: audio processing settings.
