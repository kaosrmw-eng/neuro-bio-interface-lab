# Neuro/Bio Interface Lab

A local browser laboratory for exploring Mudra Studio signals. The interface visualizes navigation, gesture, pressure, direction, IMU, SNC, and a representative spatial model. It also includes an optional low-volume auditory mapping inspired by early biofeedback devices.

## Run locally

1. Start the Mudra Studio WebSocket server at `ws://127.0.0.1:8766`.
2. Serve this directory:

   ```sh
   python3 -m http.server 4173
   ```

3. Open `http://127.0.0.1:4173/`.

The page starts in real-data mode. Mudra Studio currently accepts one WebSocket client at a time.

## Notes

- The Spatial view is representative, not anatomical.
- The biofeedback tone maps Mudra SNC and motion data; it is not a galvanic skin response measurement or a medical instrument.
- Project site: [Cafe Washburn](https://cafewashburn.com)
