# ResQ · Council Chamber

A 3D prototype of the ResQ specialist council. Five clinicians sit around a case in an
operating theatre, argue it out, and you watch the agreement and the dissent move in real
time while the next steps stay on screen.

Runs as static files. No build step.

## Local

    python3 -m http.server 5178

Then open http://localhost:5178

## What is in it

- Four cases: cardiac arrest (default), chest pain, collapse after local anaesthetic, syncope
- A live deliberation panel: what is happening, context forming, arguments, who stands where
- A next-steps window for every case, with an animated compression-only CPR demonstration
- Simulated dispatch: location, units, a hospital chosen on capability, hospital briefed
- A downloadable twelve-section deliberation report
- A sixty second film the app shoots of itself, with narration, recordable to webm

## 3D models

Doctor models are CC-BY-4.0 and may be used commercially with credit. Credits are listed
in `doctors.json` and shown in the app under "Credits".

- Doctor, Sketchfab Weekly 13 Mar 23 — BrushDip — CC-BY-4.0
- Doctor Lab — 00amza — CC-BY-4.0
- doctor — Chenchanchong — CC-BY-4.0
- Doctor — Box Games — CC-BY-4.0
- Doctor Pinch — edouard77 — CC-BY-4.0
- Doctor Administering Cpr — rwolzinger — CC-BY-4.0

The scanned operating theatre (Charité University Hospital, ChrisRE) is **CC-BY-NC-4.0,
non commercial only**, and is therefore NOT included in this repository. If you hold a
licence for it, drop it at `models/operating_room/scene.gltf` and the "Scanned room"
button will pick it up. Without it the app uses its own built room.

## Not medical advice

Every case is an illustration of designed behaviour. Nothing here is a medical record or a
treatment decision. Dispatch is simulated and contacts no service. In an emergency in
India, dial 108.
