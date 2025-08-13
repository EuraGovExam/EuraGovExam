<div align="center">
  <img src="icon12.jpg" alt="EuraGovExam icon" style="width: 70%;" />
</div>

<p align="center">
  <b>A Multilingual Multimodal Benchmark from Real‑World Civil Service Exams</b>
  <br>
</p>

<h4 align="center">
  <a href="" target="_blank">Paper (Comming Soon!)</a> |
  <a href="https://euragovexam.github.io/EuraGovExam/index.html" target="_blank">Leaderboard</a> |
  <a href="https://huggingface.co/datasets/EuraGovExam/EuraGovExam" target="_blank">Dataset</a>
</h4>

---

## Table of Contents

* [Overview](#overview)
* [Dataset](#dataset)
* [Quick Start](#quick-start)
* [Benchmark Tasks](#benchmark-tasks)
* [Baselines & Leaderboard](#baselines--leaderboard)
* [Citation](#citation)
* [License](#license)
* [Contributing](#contributing)
* [Contact](#contact)

## Overview

EuraGovExam is a high‑fidelity **multilingual** & **multimodal** benchmark built from authentic civil‑service examinations spanning **five Eurasian regions** and **17 academic / bureaucratic domains**. Each problem is provided as a single high‑resolution **image** plus four answer choices, requiring models to reason over layout, tables, diagrams and code‑switched text without additional prompts.

* **Scale:** ≈8 k scanned MCQ items
* **Languages:** Korean, Japanese, Traditional Chinese, English, Hindi
* **Domains:** Mathematics, Law, Administration, Biology, Chemistry, ... (full list below)
* **Regions:** South Korea, Japan, Taiwan, India, European Union

EuraGovExam fills the gap between synthetic academic QA sets and the messy reality of government documents, supporting research on vision‑language models, layout understanding, cross‑lingual reasoning, and instruction following.

## Dataset



### Domains

| #  | Domain           | Share |
| -- | ---------------- | ----- |
| 1  | Mathematics      | 13.0% |
| 2  | Administration   | 11.6% |
| 3  | Biology          | 11.3% |
| 4  | Law              | 10.2% |
| 5  | Language         | 9.3%  |
| 6  | Engineering      | 8.6%  |
| 7  | Physics          | 6.8%  |
| 8  | Economics        | 5.8%  |
| 9  | Computer Science | 5.5%  |
| 10 | History          | 3.2%  |
| 11 | Medicine         | 3.0%  |
| 12 | Politics         | 2.6%  |
| 13 | Chemistry        | 2.6%  |
| 14 | Geography        | 2.3%  |
| 15 | Philosophy       | 1.6%  |
| 16 | Psychology       | 1.5%  |
| 17 | Earth Science    | 1.5%  |

### Download via 🤗 datasets

```python
from datasets import load_dataset
ds = load_dataset("EuraGovExam/EuraGovExam")
```



## Baselines & Leaderboard

See the **public leaderboard** for up‑to‑date results. Key snapshot (July 2025):

| Model              | Params | Accuracy   |
| ------------------ | ------ | ---------- |
| GPT‑4.1            | —      | **54.7 %** |
| GPT‑4o             | —      | 42.0 %     |
| Claude‑Sonnet‑4    | —      | 46.8 %     |
| Llama‑3‑Vision‑11B | 11 B   | 10.6 %     |
| Gemma‑3‑32B‑it     | 32 B   | 19.4 %     |

More details in [`/data/leaderboard.json`](/data/leaderboard.json).

## Citation

If you use EuraGovExam, please cite:

```bibtex
@inproceedings{euragovexam2026,
  title     = {EuraGovExam: A Multilingual Multimodal Benchmark from Real‑World Civil Service Exams},
  author    = {First Author and Second Author and others},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence},
  year      = {2026}
}
```

## License

EuraGovExam is released under the **CC BY‑NC 4.0** license. See [`LICENSE`](LICENSE) for details.

## Contributing

Pull requests are welcome! Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) first and be mindful of regional examination copyright.

## Contact

**Comming Soon!**

