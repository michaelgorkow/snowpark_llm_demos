# Snowpark & Large Language Models (LLMs)
Demos &amp; Tutorials for using Snowpark and LLMs

## Requirements
- A [Snowflake Account](https://signup.snowflake.com/) 
- [Anaconda Integration enabled by ORGADMIN](https://docs.snowflake.com/en/developer-guide/udf/python/udf-python-packages#getting-started)

## Setup
First, clone the source code for this repo to your local environment:
```bash
git clone https://github.com/michaelgorkow/snowpark_llm_demos
cd snowpark_llm_demos
```

If you are using [Anaconda](https://www.anaconda.com/products/distribution) on your local machine, create a conda env from the provided environment yml-file:
```bash
conda env create -f conda_environment.yml
conda activate py_snowpark_llm
```
Conda will automatically install `snowflake-snowpark-python` and all other dependencies for you.

Now, launch Jupyter Notebook on your local machine:
```bash
jupyter notebook
```

## Blog Articles
[Snowflake External Access & OpenAIs ChatGPT](https://medium.com/@michaelgorkow/snowflake-external-access-openais-chatgpt-766068a8a967?source=friends_link&sk=bf883aa9798f451abca0555249611438)
