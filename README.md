# FAQ Generator

## Overview
The **FAQ Generator** is a tool designed to automate the process of generating Frequently Asked Questions (FAQs) based on input data. It leverages NLP techniques to extract key information and structure it into a Q&A format, making it useful for documentation, customer support, and knowledge bases.

## Features
- Automatic question generation from text sources
- Customizable answer formatting
- Supports multiple input formats (text, JSON, CSV, etc.)
- Simple and efficient implementation

## Installation
Clone the repository and install the required dependencies:

```sh
git clone https://github.com/ronitmalvi/FAQ-gen.git
cd FAQ-gen
pip install -r requirements.txt
```

## Usage
Run the FAQ generator with:

```sh
python faq_generator.py --input data.txt --output faq.json
```

### Arguments:
- `--input` : Path to the input file (text, CSV, JSON)
- `--output` : Path to the generated FAQ file

## Configuration
Modify the `config.json` file to customize settings such as output format, question structure, and processing parameters.

## Example
Input (`data.txt`):
```
Machine learning is a field of AI that enables computers to learn from data.
Supervised learning and unsupervised learning are the two main types.
```

Output (`faq.json`):
```json
{
  "questions": [
    "What is machine learning?",
    "What are the main types of machine learning?"
  ],
  "answers": [
    "Machine learning is a field of AI that enables computers to learn from data.",
    "Supervised learning and unsupervised learning are the two main types."
  ]
}
```

## Contributing
Feel free to submit issues or pull requests to improve the project.

## License
This project is licensed under the MIT License.

## Contact
For any queries, reach out to [Ronit Malvi](https://github.com/ronitmalvi).
