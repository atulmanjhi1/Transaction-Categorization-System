# Transaction Categorization System

This Python script categorizes financial transactions listed in a CSV file. It utilizes natural language processing (NLP) models to automatically assign categories to each transaction based on its description.

## Features

- **Automatic Categorization**: Utilizes NLP models to automatically categorize transactions.
- **Data Processing**: Cleans and preprocesses transaction data before categorization.
- **Flexible Categorization Rules**: Allows customization of categorization rules based on keywords.
- **Output CSV**: Generates a new CSV file with categorized transactions.

## Installation

1. Clone this repository to your local machine.
2. Install the required Python packages using pip:

```bash
pip install langchain_community pandas
```

## Usage

1. Ensure your transaction data is in CSV format with a column named "Name / Description".
2. Replace the file path in the script with the path to your CSV file.
3. Run the script:

```bash
python categorize_transactions.py
```

4. Once the script completes execution, you will find a new CSV file named `transactions_categorized.csv` with categorized transactions.

## Customization

- Adjust the batch size in the `index_list` to optimize processing based on your dataset size.
- Modify the categorization rules in the code to suit your specific needs.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests to suggest improvements or report bugs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

Feel free to adjust the content to fit your project's specifics!