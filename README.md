
# Text Summarization Using Hugging Face 

This project demonstrates how to perform text summarization using the Hugging Face Transformers library. The application allows users to input any text and generates a concise summary of it. This can be particularly useful for quickly digesting large amounts of information from articles, reports, or any text data.

## Features
- **User Input**: Allows users to enter any text for summarization.
- **Summarization**: Utilizes a pre-trained BART model to summarize the provided text.
- **Exit Option**: Users can exit the application by typing 'exit'.

## Prerequisites

1. **Python**: Ensure you have Python 3.7 or higher installed on your machine.
2. **Install Required Libraries**:
   - Install the necessary packages by running:
     ```bash
     pip install transformers
     ```


## Usage

1. **Run the Script**:
   To execute the text summarization tool, run the following command:
   ```bash
   python text_summarization.py
   ```

   Replace `text_summarization.py` with the filename if you name it differently.

2. **Input Text**:
   Enter the text you want to summarize when prompted. 

3. **View Summary**:
   The program will output the summarized version of the input text.

4. **Exit the Application**:
   Type `exit` to quit the application.


## Customization

Feel free to customize the model used for summarization by changing the model name in the `TextSummarizer` class constructor. You can explore different models available on the Hugging Face Model Hub: [Hugging Face Model Hub](https://huggingface.co/models).

