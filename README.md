# OOPs Project deploying Natural languague processing(NLP)

## How to run

1. Creating a virtual conda environment through jupyter notebook or google colab with python3

```bash 
conda create -n envname python=3.9
```
2. Checkout the created virtual environment
```bash
conda env list
```
3. Actiavte the virtual environment

```bash
conda activate envname
```
3. While working with VS studio require specific python version 3.9 and above

4. Install the required generativeai package

```bash
!pip install google-generativeai
```
5. create **parent class** NLPmodel for required generativeai application
6. create **child class** NLPapp for applying all kind of functionalities
