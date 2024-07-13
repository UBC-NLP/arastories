# AraStories: Arabic Automatic Story Generation with Large Language Models


This repository contains the code and data related to our paper [AraStories: An Extensive Benchmark and Dataset for Arabic Story Understanding and Commonsense Reasoning](https://arxiv.org/abs/2407.07551), published on arXiv.

## Overview

**AraStories** is a comprehensive benchmark and dataset designed to facilitate research in the areas of story understanding and commonsense reasoning in Arabic. The dataset includes a wide variety of stories and corresponding questions that challenge models to exhibit a deep understanding of narrative structures and commonsense knowledge in the Arabic language.

## Contents

- `data/`: Contains the AraStories dataset in various formats.
- `src/`: Source code for preprocessing, training, and evaluation.
- `models/`: Pre-trained models and checkpoints.
- `notebooks/`: Jupyter notebooks for data exploration and analysis.
- `results/`: Results and evaluation metrics.

## Dataset

The AraStories dataset consists of:

- **Stories**: A diverse collection of Arabic stories from various genres and sources.
- **Questions**: Questions related to the stories designed to test different aspects of story understanding and commonsense reasoning.
- **Annotations**: Human-annotated answers and rationales.

### Download

You can download the dataset from the following link:

[Download AraStories Dataset](https://example.com/download)

## Getting Started

### Prerequisites

- Python 3.10+
- Required Python libraries are listed in `requirements.txt`.

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/UBC-NLP/arastories.git
   cd arastories
   ```

2. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

### Usage

#### Preprocessing

To preprocess the data, run the following command:
```sh
python src/preprocess.py --input data/raw --output data/processed
```

#### Training

To train a model on the AraStories dataset, use:
```sh
python src/train.py --config configs/train_config.json
```

#### Evaluation

To evaluate a trained model, run:
```sh
python src/evaluate.py --model models/model_checkpoint.pth --data data/processed
```

### Jupyter Notebooks

Explore the dataset and results using the provided Jupyter notebooks in the `notebooks/` directory.

## Results

We provide benchmark results for various models trained on the AraStories dataset. Detailed results and evaluation metrics are available in the `results/` directory.

## Citation

If you use AraStories in your research, please cite our paper:

```bibtex
@misc{elshangiti2024arabicautomaticstorygeneration,
      title={Arabic Automatic Story Generation with Large Language Models}, 
      author={Ahmed Oumar El-Shangiti and Fakhraddin Alwajih and Muhammad Abdul-Mageed},
      year={2024},
      eprint={2407.07551},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2407.07551}, 
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank the contributors and collaborators who made this project possible.

---

Feel free to modify and expand upon this template to better suit your project's specifics and your preferences.
