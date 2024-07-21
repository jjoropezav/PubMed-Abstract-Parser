# PubMed Abstract Parser

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Vz1iQmMI7fL5WPdkFGiNvEehpGSzCexB?usp=sharing)

## Overview

This repository contains a Jupyter Notebook that demonstrates how to fetch and process abstracts from PubMed using the BioPython library. The notebook provides a streamlined workflow for retrieving scientific abstracts based on specified keywords, parsing the data, and saving it into a structured CSV file for further analysis.

## Features

- Fetches abstracts from PubMed based on user-defined keywords
- Extracts key information such as title, authors, journal, publication date, DOI, and more
- Handles text encoding and normalization
- Saves parsed data into a CSV file

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python packages:
  - biopython
  - unidecode
  - pandas
  - numpy

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/Pubmed-Abstract-Parser.git
   cd Pubmed-Abstract-Parser
   ```

2. Install the required packages:
   ```
   pip install biopython unidecode pandas numpy
   ```

3. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

4. Open the `Abstract_parser_PUBMED.ipynb` notebook in your Jupyter environment.

## Usage

1. Set up your email for NCBI's Entrez:
   - In the notebook, replace `"example@email.com"` with your email address.

2. Define your keywords:
   - Modify the `keywords` list to include the terms you want to search for in PubMed.

3. Set the maximum number of abstracts to fetch:
   - Adjust the `max_count` parameter in the `fetch_abstracts` function call to control the number of abstracts retrieved per keyword.

4. Run the notebook cells sequentially to:
   - Fetch abstracts from PubMed
   - Process and clean the data
   - Save the results to a CSV file

5. The resulting CSV file will be saved in the same directory as the notebook.

## Customization

You can easily modify the notebook to suit your specific needs:

- Add or remove fields in the `fetch_abstracts` function
- Adjust the data cleaning steps
- Modify the CSV output format

## Contributing

Contributions to improve the notebook or extend its functionality are welcome. Please feel free to submit pull requests or open issues for any bugs or feature requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- BioPython for providing the tools to interact with PubMed
- NCBI for maintaining the PubMed database and providing programmatic access

## Contact

For any questions or concerns, please open an issue in this repository or contact the repository owner.

---

Developed by PhD Juan José Oropeza Valdez, July 2024
