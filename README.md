# COrpus of Oz Early English (COOEE)

## Overview

**Keywords**: Australian and New Zealand English; Corpus linguistics

The [COrpus of Oz Early English (COOEE)](https://researchdata.edu.au/corpus-oz-early-english/2013) is an innovative linguistic project aimed at creating a comprehensive digital repository of English language usage in Australia from its **early colonial period** through to the **early 20th century**. 

It compiles a diverse range of texts, including **letters**, **newspapers**, **legal documents**, **diaries**, and **literary works**, offering a rich and multifaceted perspective on the language used by Australia’s early settlers, convicts, and indigenous peoples interacting with English. 


## Data Source

The original data is downloaded from [LDaCA - A COrpus of Oz Early English (COOEE)](https://data.ldaca.edu.au/collection?id=arcp%3A%2F%2Fname%2Cdoi10.26180%252F23961609&_crateId=arcp%3A%2F%2Fname%2Cdoi10.26180%252F23961609) and licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en).

The cleaned data under `COOEE_clean` is created by [Yifan Luo](https://github.com/iamyifan). You can also find this dataset from [Hugging Face - SouthernCrossAI/COOEE_The_Corpus_of_Oz_Early_English](https://huggingface.co/datasets/SouthernCrossAI/COOEE_The_Corpus_of_Oz_Early_English).


## Dataset Structure

The dataset under `COOEE/COOEE` includes 1357 plain `.txt` files and 1 metadata `.json` file collected from [LDaCA - A COrpus of Oz Early English (COOEE)](https://data.ldaca.edu.au/collection?id=arcp%3A%2F%2Fname%2Cdoi10.26180%252F23961609&_crateId=arcp%3A%2F%2Fname%2Cdoi10.26180%252F23961609). It is arranged in the following two ways:

- **Time period** - The corpus is divided into four time periods (the initial numeral of each file name indicates the period from which the document comes): 
  - Period 1 (1788-1825): includes 268 `.txt` files, e.g., `1-001-plain.txt`.`
  - Period 2 (1826-1850): includes 364 `.txt` files, e.g., `2-001-plain.txt`.`
  - Period 3 (1851-1875): includes 306 `.txt` files, e.g., `3-001-plain.txt`.
  - Period 4 (1876-1900): includes 419 `.txt` files, e.g., `4-001-plain.txt`.
- **Register** - The corpus contains material from four registers (the register to which a file belongs is specified in the **metadata** at the start of each file in the form <r=[register]> using the abbreviations above):
  - Speech-based (sb)
  - Private written (prw)
  - Public written (pcw)
  - Government English (ge)


## Download

You can install the dependencies and download the dataset by running `utils/download.ipynb`. 

The notebook is modified from [GitHub - Australian-Text-Analytics-Platform/cooee](https://github.com/Australian-Text-Analytics-Platform/cooee). For using LDaCA's API services, you need to register a [LDaCA](https://data.ldaca.edu.au/) account, and store your API key in `utils/vars.env`.


## License

This repository is licensed under [MIT](https://opensource.org/license/mit).
