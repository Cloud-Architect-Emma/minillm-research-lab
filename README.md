# MiniLLM Research Lab

**Building, Training and Optimising a GPT-Style Language Model from Scratch**

## Research Objective

Investigate how model architecture and training configurations affect the quality and computational efficiency of small transformer language models under limited computing resources.

## Research Questions

1. How does transformer model size affect validation loss?
2. How do training configurations affect learning efficiency?
3. What trade-offs exist between model quality, training speed and memory usage?

## Technology Stack

- Python
- PyTorch
- Google Colab
- GitHub
- Matplotlib
- Hugging Face (planned)

## Research Methodology

1. Prepare and validate a text dataset.
2. Implement a tokenizer.
3. Build a GPT-style transformer from scratch.
4. Train a baseline model.
5. Measure validation loss and training performance.
6. Run controlled experiments.
7. Analyse results and document findings.

## Project Progress

- [x] Lab 1: Data preparation and character-level tokenizer
- [ ] Lab 2: Transformer architecture
- [ ] Lab 3: Model training and optimisation
- [ ] Lab 4: Model evaluation and inference
- [ ] Lab 5: Controlled research experiments
- [ ] Lab 6: Performance optimisation
- [ ] Lab 7: Research report and reproducibility

## Dataset

Initial experiments use the Tiny Shakespeare dataset from Andrej Karpathy's char-rnn repository.

Source: https://github.com/karpathy/char-rnn

## Research Status

Initial implementation in progress. Experimental results will be published after training and evaluation.

## Reproducibility

Run the notebooks in numerical order. Each experiment will document its configuration, random seed, dataset, environment and results.

## Limitations

The initial model and dataset are intentionally small. Findings from these experiments may not generalise to large language models.
