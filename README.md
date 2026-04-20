# Flappy Bird with NEAT AI

This project is a Flappy Bird clone where the game learns to play itself using the NEAT algorithm.

## What was done

- Implemented the Flappy Bird game logic in `main.py`.
- Added training and gameplay support using the `neat-python` library.
- Included a NEAT configuration file: `config-feedforward.txt`.
- Added game assets in `assets/` for the bird, pipes, background, and base.
- Included a demo video showing the trained AI playing the game: `assets/ResultVid.mp4`.

## Files in this project

- `main.py` - the game and training loop.
- `config-feedforward.txt` - NEAT configuration settings for evolving the neural network.
- `requirement.txt` - required Python packages (`neat-python`, `pygame`).
- `assets/` - contains sprites and the demo video.

## Requirements

Install the dependencies before running the project:

```bash
pip install -r requirement.txt
```

## How to run

Run the main script to start the game and training process:

```bash
python main.py
```

## Demo video

The video demonstrating the AI playing Flappy Bird is available in the repository:

<video controls width="640" height="360">
  <source src="assets/ResultVid.mp4" type="video/mp4">
  Your browser does not support the video tag. You can download the video directly from `assets/ResultVid.mp4`.
</video>

If the video does not display in your Markdown viewer, open `assets/ResultVid.mp4` directly.

## Notes

This project uses a genetic algorithm approach to evolve bird agents over successive generations. The final AI learns to navigate through pipes by selecting when to flap.

