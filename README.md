# README.md

---

# Ipython Notebook Repository for LLama2 with Langchain Use Cases 

---

This repository provides Ipython Notebook examples for how to use LLama2 in combination with Langchain. LLama2 is recently released model by Meta. This notebook is prepared for the OpenNyAI Makerspace (https://makerspace.opennyai.org/). Given that GPT4 is difficult and expensive to access we have hosted a 70b llam2 model which works quite well.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Notebook](#notebooks)
- [Usage](#usage)
- [Contribution](#contribution)
- [License](#license)

---

## Prerequisites

* Python 3.8 or newer
* Jupyter Notebook
* Mac OS Ventura M1 with 16gb RAM

---

## Installation

Clone the repository:

```
git clone https://github.com/OpenNyAI/llm_samples.git
```

Create a new Python environment:

```
python3 -m venv env
source env/bin/activate
```

Install the requirements:

```
pip install -r requirements.txt
```

---

## Notebooks

**Getting Started with LLama2 and Langchain.ipynb**: An introduction to using LLama2 and Langchain separately and then combining them. The model has to be hosted on one of the availabel GPUs. This one uses 70b parameter model hosted on OpenNyAI's cloud account, however similar code can be used when hosting a 7b or 13b model on device.

---

## Usage

To run the notebooks, start Jupyter Notebook from the command line:

```
jupyter notebook
```

Navigate to the notebook you want to open in your browser.

---

## Contribution

Contributions are welcomed! Please fork this repository and open a pull request to add more notebooks, make grammar tweaks, etc.

---

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

---

Please feel free to reach out if you encounter any issues or need further explanation of any notebook. Enjoy exploring the power of LLama2 and Langchain!
