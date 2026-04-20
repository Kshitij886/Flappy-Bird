# 🐦 Flappy Bird AI with NEAT

A Flappy Bird clone that learns to play itself using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm.

## 🚀 Features

* Fully implemented Flappy Bird game using `pygame`
* AI training using `neat-python`
* Neural networks evolve over generations
* Real-time simulation of multiple birds learning simultaneously

---

## 📁 Project Structure

```
.
├── main.py                  # Game loop + NEAT training
├── config-feedforward.txt  # NEAT configuration
├── requirement.txt         # Dependencies
└── assets/                 # Images + demo video
```

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install -r requirement.txt
```

---

## ▶️ Run the Project

```bash
python main.py
```

This will start training the AI.
At first, the birds will perform terribly (as expected). Over generations, they improve.

---

## 🎥 Demo

👉 [Watch the demo video](assets/ResultVid.gif)

> Tip: GitHub does not support embedded video playback in README files.
> Download or open the video manually if it doesn't preview.

---

## 🧠 How It Works

* Each bird is controlled by a neural network
* Inputs:

  * Bird's vertical position
  * Distance to top pipe
  * Distance to bottom pipe
* Output:

  * Whether the bird should jump

NEAT evolves these networks using:

* Mutation
* Crossover
* Natural selection (fitness-based)

---

## 📌 Notes

* Training is stochastic — results may vary
* Adjust `config-feedforward.txt` to experiment with evolution behavior
* Performance improves significantly after multiple generations

---

## 💡 Future Improvements

* Save/load best model
* Visualize neural networks
* Add speed controls for faster training
* Improve fitness function

---

## 🧪 Dependencies

* pygame
* neat-python

---

## 📜 License

MIT License
