# AI & Machine Learning Portfolio

Selected academic implementations by **Kauan Abegg**, Control and Automation Engineering student at UFSC.

A curated guide to my academic AI implementations and LLM integration work. The repositories include source code, setup instructions, documented evidence, limitations and academic credits.

Start with **[AI-Powered Phishing Detection](https://github.com/abeggg/AI-Powered-Phishing-Detection)** for an applied LLM workflow and **[Neural Networks from Scratch](https://github.com/abeggg/neural-networks-from-scratch)** for mathematical implementation.

[Try the public phishing dashboard](https://abeggg.github.io/AI-Powered-Phishing-Detection/) — synthetic records; no credentials or live inference.

| Repository | Main topics | Evidence and scope |
| --- | --- | --- |
| [AI-Powered Phishing Detection](https://github.com/abeggg/AI-Powered-Phishing-Detection) | n8n, Groq/Llama, JavaScript, Supabase | Importable workflow, defensive validation and public synthetic dashboard; revised n8n runtime integration remains untested |
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

These projects cover ML, deep learning, reinforcement learning, search, automated planning and an applied LLM integration. The autoencoders are deterministic. The phishing project uses an existing model through Groq; its public dashboard displays saved or synthetic classifications and is not connected directly to Supabase. Precision, recall and F1 have not been established for the phishing classifier. See each repository for the distinction between recorded results, offline checks and runtime validation.

Academic context, instructor contributions and AI assistance are described in the individual repositories. No blanket license has been assigned to course-provided datasets or templates.

## Software projects

- [AudioDuplo](https://github.com/abeggg/AudioDuplo): native Windows audio routing in C++20/WASAPI.
- [Clima Flow Demo](https://github.com/abeggg/Clima-Flow-Demo): React service-management demo with fictional records.

[GitHub profile](https://github.com/abeggg)
