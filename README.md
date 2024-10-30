# Azure Text Analysis Tool

This is a Python-based tool for analyzing text files using Azure's Cognitive Services for natural language processing (NLP). It performs multiple types of text analyses, such as language detection, sentiment analysis, key phrase extraction, named entity recognition, and linked entity recognition.

## Features

- **Language Detection**: Identifies the language of each text file.
- **Sentiment Analysis**: Determines the overall sentiment (positive, neutral, negative) of the text.
- **Key Phrase Extraction**: Extracts significant phrases from the text to give an overview of key points.
- **Named Entity Recognition (NER)**: Identifies and categorizes entities in the text, such as people, organizations, locations, and more.
- **Linked Entity Recognition**: Recognizes entities in the text and links them to related information from the web.

## Future Enhancements

- **Automated Sentiment Tracking**: Implement a method for continuous sentiment tracking over time by logging and visualizing data changes.
- **Enhanced Error Handling**: Add detailed error-handling mechanisms for improved debugging and reliability.
- **Web Interface**: Develop a front-end dashboard to display results in real-time using graphical visualizations.
- **Automated Azure Service Setup**: Add scripts to simplify the setup of Azure Cognitive Services and streamline the environment configuration.

## Prerequisites

- Python 3.x
- Azure Cognitive Services account with Text Analytics enabled
- A `.env` file with the following configuration:
  ```plaintext
  AI_SERVICE_ENDPOINT=<Your Azure Cognitive Service Endpoint>
  AI_SERVICE_KEY=<Your Azure Cognitive Service Key>
  ```

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/azure-text-analysis-tool.git
   cd azure-text-analysis-tool
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the project directory and add your Azure endpoint and key.

4. **Create a Folder with Text Files**:
   - Place text files in a folder named `reviews` in the root directory. Each file should contain text data you wish to analyze.

## Usage

To run the analysis, execute:

```bash
python main.py
```

The output includes language detection, sentiment analysis, key phrases, recognized entities, and linked entities for each file in the `reviews` folder.


## Azure Cognitive Services Setup

For setting up Azure Cognitive Services for Text Analytics, refer to the [official Azure documentation](https://docs.microsoft.com/azure/cognitive-services/text-analytics/) for detailed steps.

## Contributing

Contributions are welcome! If you would like to add new features or improve existing code, please submit a pull request.
