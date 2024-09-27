# Clinical Text Analysis for Outcome Prediction

This repository contains the implementation of the research paper "Preserving Knowledge of Long Clinical Texts Using Aggregated Ensembles of Large Language Models" available at [https://arxiv.org/abs/2311.01571](https://arxiv.org/abs/2311.01571).

## Abstract

Clinical texts, such as admission notes, discharge summaries, and progress notes, contain rich and valuable information that can be used for various clinical outcome prediction tasks. This project addresses two major challenges in applying large language models to clinical texts: the limitation of input length and the diversity of data sources. We propose a novel method to preserve the knowledge of long clinical texts using aggregated ensembles of large language models.

## Key Features

- Combines ensemble learning with text aggregation
- Trains multiple large language models on two clinical outcome tasks:
  - Mortality prediction
  - Length of stay prediction
- Achieves better results than baselines, ensembling, and aggregation individually
- Improves performance of large language models while handling long inputs and diverse datasets

## Implementation

The project is implemented using:
- PyTorch Framework
- Hugging Face Transformers
- Other associated libraries like NumPy, Pandas.

## Dataset

The experiments are conducted on admission notes from the MIMIC-III clinical database, combining multiple unstructured and high-dimensional datasets.

## Results

Our method demonstrates:
- Effectiveness in handling long clinical texts
- Superiority over existing approaches
- Potential applications in clinical decision-making systems

## Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/clinical-text-analysis.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Open and run the Jupyter notebooks:
   ```
   jupyter notebook
   ```

## Citation

If you use this code or find our research useful for your work, please cite our paper:

```
@article{author2023preserving,
  title={Preserving Knowledge of Long Clinical Texts Using Aggregated Ensembles of Large Language Models},
  author={Author, A. and Author, B.},
  journal={arXiv preprint arXiv:2311.01571},
  year={2023}
}
```

## Contributing

We welcome contributions to improve DeepMarkerNet. Please feel free to submit issues and pull requests.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any queries regarding the code or paper, please open an issue or contact Mohammad Junayed Hasan (mailto:junayedhasan100@gmail.com).

---

Copyright © 2024 Mohammad Junayed Hasan. All rights reserved.
