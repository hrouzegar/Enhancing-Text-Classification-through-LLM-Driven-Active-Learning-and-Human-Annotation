# Enhancing Text Classification through LLM-Driven Active Learning and Human Annotation

This repository contains the official implementation, experimental notebooks, and supplemental materials for our paper presented at the **18th Linguistic Annotation Workshop (LAW-XVIII), 2024**.

**Authors:**
- [Hamidreza Rouzegar](mailto:hamidreza.rouzegar@ontariotechu.net)
- [Masoud Makrehchi](mailto:masoud.makrehchi@ontariotechu.ca)

## Overview

We introduce a novel methodology integrating human annotators and GPT-3.5 annotations within an Active Learning framework for text classification. This approach significantly reduces annotation costs while maintaining or improving classification accuracy.

## Paper Information

- **Anthology ID:** [2024.law-1.10](https://aclanthology.org/2024.law-1.10/)
- **Conference:** 18th Linguistic Annotation Workshop (LAW-XVIII)
- **Date & Location:** March 22, 2024, St. Julians, Malta
- [Paper Link](https://aclanthology.org/2024.law-1.10.pdf)

## Datasets

We evaluated our methodology using the following datasets:

- **IMDB Reviews**: Binary sentiment classification (positive/negative).
- **Fake News**: Binary classification for detecting fake vs. authentic news articles.
- **Movie Genres**: Multi-label genre classification based on movie plots.

Each dataset is included in this repository with corresponding preprocessing scripts and experimental notebooks.

## Repository Structure

- `Fake News Code.ipynb`: Active learning experiments on the Fake News dataset.
- `Zero shot.ipynb`: Demonstrates zero-shot annotation using GPT-3.5.
- `Few-shot learning.ipynb`: Implements few-shot annotation methods.
- `New_Few_fake_news.csv`, `New_Few_movies_genre.pkl`, `New_Few_fake_news.csv`: Dataset files.
- `README.md`: Documentation and repository details.

## Running the Code

### Requirements

To install the required libraries:

```bash
pip install -r requirements.txt
```

### Instructions

- Run dataset-specific notebooks (e.g., `Fake News Code.ipynb`) for detailed experimental results.
- Refer to `Zero shot.ipynb` and `Few-shot learning.ipynb` for guidance on prompt design and GPT-3.5 API usage.
- Use provided scripts for visualizing experimental outcomes (`plot_results.ipynb`).

## Citation

If you use our work, please cite:

```bibtex
@article{rouzegar2024enhancing,
  title={Enhancing text classification through llm-driven active learning and human annotation},
  author={Rouzegar, Hamidreza and Makrehchi, Masoud},
  journal={arXiv preprint arXiv:2406.12114},
  year={2024}
}
```

## Contact

For questions or further collaboration, please reach out to:

- Hamidreza Rouzegar ([hamidreza.rouzegar@ontariotechu.net](mailto:hamidreza.rouzegar@ontariotechu.net))
- Masoud Makrehchi ([masoud.makrehchi@ontariotechu.ca](mailto:masoud.makrehchi@ontariotechu.ca))

## License

This repository is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

