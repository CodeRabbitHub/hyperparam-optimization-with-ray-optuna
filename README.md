# Optuna-Ray Hyperparameter Tuning

![Python](https://img.shields.io/badge/python-v3.12.4-blue)
![Optuna](https://img.shields.io/badge/Optuna-v3.x-orange)
![Ray](https://img.shields.io/badge/Ray-v2.x-green)
![XGBoost](https://img.shields.io/badge/XGBoost-v1.x-red)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

## Overview

This project demonstrates how to perform parallel hyperparameter tuning using [Optuna](https://optuna.org/) and [Ray](https://docs.ray.io/en/latest/) on a large-scale dataset. Leveraging 96 CPUs, it showcases efficient hyperparameter optimization for an XGBoost model. Additionally, it provides insights into handling Ray objects when working with large datasets, ensuring scalable and efficient tuning.

## Project Structure

```plaintext
├── .gitignore
├── LICENSE
├── README.md
├── requirements.txt
├── test.csv
├── train.csv
├── training.ipynb
└── validation.csv
```

- **.gitignore**: Specifies files and directories to be ignored by git.
- **LICENSE**: The license under which this project is distributed.
- **README.md**: Provides an overview and instructions for the project.
- **requirements.txt**: Lists the Python dependencies required to run the project.
- **test.csv**, **train.csv**, **validation.csv**: Datasets used for training, validation, and testing.
- **training.ipynb**: A Jupyter notebook containing the implementation of the hyperparameter tuning process using Optuna and Ray.

## Key Features

- **Parallel Hyperparameter Tuning**: Harness the power of 96 CPUs to perform hyperparameter tuning in parallel, significantly reducing the time required for model optimization.
  
- **Scalable Ray Objects**: Learn how to handle Ray objects efficiently, enabling the management of large datasets in a distributed environment.
  
- **XGBoost Integration**: Fine-tune an XGBoost model with Optuna's state-of-the-art optimization algorithms.

## Prerequisites

- Python 3.12.4
- Jupyter Notebook
- [Ray](https://docs.ray.io/en/latest/)
- [Optuna](https://optuna.org/)
- [XGBoost](https://xgboost.readthedocs.io/)

Ensure you have the required dependencies installed:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/CodeRabbitHub/hyperparam-optimization-with-ray-optuna.git
   cd hyperparam-optimization-with-ray-optuna
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:

   ```bash
   jupyter notebook training.ipynb
   ```

4. Follow the steps in the notebook to perform hyperparameter tuning.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize the repository link and any other details as needed!