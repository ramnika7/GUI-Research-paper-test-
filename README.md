# GUI-Research-paper-test-
This file talks of the test results of inter device AI models and their efficiency  to  carry  out cross device work.
# GUI Inter-Device Task Benchmark

## Overview
This repository evaluates cross-device AI model efficiency and execution success rates across complex multi-step GUI workflows.

## Key Performance Metrics

| Metric | Score | 95% Confidence Interval | Sample Size |
| :--- | :--- | :--- | :--- |
| **Total Task Success Rate (TSR)** | 60.0% | [30.0%, 90.0%] | 10 task graphs |
| **Sub-task Success Rate (SSR)** | 76.7% | [56.7%, 93.3%] | 30 total subtasks |

## Methodology & Experimental Setup
- **Evaluated Models:** [Specify model name, e.g., GPT-4o, Claude 3.5]
- **Environment:** Cross-device GUI automation environment
- **Execution Log:** Refer to [`results.log`](./results.log) for full execution outputs.
- 
## Citation & Acknowledgements

This repository is an independent implementation based on the research presented in:

> **JarvisGUI: Towards Cross-Device GUI Agents with Dynamic Task Composition**  
> *Chen et al., EMNLP 2026*

If you use or reference this codebase in your work, please cite the original paper:

```bibtex
@inproceedings{chen2026jarvisgui,
  title={JarvisGUI: Towards Cross-Device GUI Agents with Dynamic Task Composition},
  author={Chen, et al.},
  booktitle={Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  year={2026}
}
