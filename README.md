# AI & Machine Learning Portfolio

Selected academic implementations by **Kauan Abegg**, Control and Automation Engineering student at UFSC.

This index connects six focused repositories. Each includes source code, installation instructions, experimental evidence, limitations and academic credits.

| Repository | Main topics | Evidence and scope |
| --- | --- | --- |
| [Neural Networks from Scratch](https://github.com/abeggg/neural-networks-from-scratch) | NumPy, backpropagation, classification | Eight-configuration pipeline reproduced; 86.96% accuracy on 23 test examples; numerical gradient check |
| [Reinforcement Learning: Mountain Car](https://github.com/abeggg/reinforcement-learning-mountain-car) | Q-Learning, SARSA, dynamic programming | 40 saved runs, multi-seed metrics and five mathematical checks; full training not repeated during preparation |
| [Intelligent Elevator Search](https://github.com/abeggg/intelligent-elevator-search) | BFS, A*, heuristic search | Source recovered from the original report; all 21 costs and expansion counts reproduced |
| [CNNs and Autoencoders](https://github.com/abeggg/cnn-autoencoders-pytorch) | MNIST, PyTorch, MLP/CNN autoencoders | Saved classifier accuracy of 99.01%; reconstruction metrics and plots; shapes/ranges/gradients checked without retraining |
| [DARP Automated Planning](https://github.com/abeggg/darp-automated-planning) | PDDL, routing, exact optimization | Oracle costs 7/17/11/48; stored plans replayed; medium STRIPS instance solved with Pyperplan |
| [Linear Regression from Scratch](https://github.com/abeggg/linear-regression-from-scratch) | Batch gradient descent, scaling, vectorization | Optimizer reproduced and checked against a closed-form reference |

## How to explore

Start with neural networks for the mathematical implementation, reinforcement learning for evaluation across seeds, and CNNs/autoencoders for PyTorch experiments. The search and planning repositories show discrete reasoning and constrained optimization. Linear regression provides a compact optimization example.

The repositories preserve the original academic algorithms. New verification scripts and workflows complement the saved experiment outputs; they do not imply that every training run was repeated. Each repository's `VALIDATION.md` describes its checks.

## Scope

These projects demonstrate foundations in ML, deep learning, reinforcement learning, search and automated planning. The autoencoders are deterministic. No VAE extension, LLM application, RAG system, fine-tuned language model, Kaggle participation or Hugging Face publication is claimed.

Academic context, instructor contributions and AI assistance are described in the individual repositories. No blanket license has been assigned to course-provided datasets or templates.

## Software projects

- [AudioDuplo](https://github.com/abeggg/AudioDuplo): native Windows audio routing in C++20/WASAPI.
- [Clima Flow Demo](https://github.com/abeggg/Clima-Flow-Demo): React service-management demo with fictional records.

[GitHub profile](https://github.com/abeggg)
