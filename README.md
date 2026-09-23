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
- Baseline GUI evaluated:
- 1) UI Venus Ground - 7B(2025)
  2) UI TARS -1.5-7-B (2025)
  3) MAI-UI-8B(2025)
  4) Gui OWL -32B
  5) Qwen3-VL-30B-A3B-Instruct (2025a)
  6) HOLO2-30B-A3B(H-company-2025)
  
  -LLM as a judge -
**Qwen3-30B-A3B-Thinking-2507-FP8
- Environment: Cross-device GUI automation environment
- Execution Log: Refer to [`results.log`](./results.log) for full execution outputs.
- 
## Citation & Acknowledgements

This repository is an independent implementation based on the research presented in:

> **JarvisGUI: Towards Cross-Device GUI Agents with Dynamic Task Composition**  
> *Chen et al., EMNLP 2026*


```bibtex
@inproceedings{chen2026jarvisgui,
  title={JarvisGUI: Towards Cross-Device GUI Agents with Dynamic Task Composition},
  author={Chen, et al.},
  booktitle={Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  year={2026}
}
