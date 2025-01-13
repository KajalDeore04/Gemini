
# Project Overview

This project utilizes the Google Generative AI API to create a conversational AI model. The model is based on the Gemini 2.0 Flash Exp model, a state-of-the-art language model capable of generating human-like text.

## Getting Started

### Prerequisites

- Node.js installed on your system
- A Google Cloud API key with the Generative AI API enabled

### Installation

1. Clone the repository to your local machine.
2. Install the required dependencies by running `npm install` in the project directory.
3. Replace `Your API Key` with your actual Google Cloud API key in the `index.js` file.

### Usage

1. Import the `run` function in your JavaScript file.
2. Call the `run` function with a prompt as an argument, like this:
   ```javascript
   run("Hello, how are you?");
   ```
3. The function will return the response from the conversational AI model as a string.

## Configuration

The conversational AI model can be configured using the `generationConfig` object. The following options are available:

- **temperature**: Controls the randomness of the generated text (default: `1`)
- **topP**: Controls the percentage of top tokens to consider when generating text (default: `0.95`)
- **topK**: Controls the number of top tokens to consider when generating text (default: `40`)
- **maxOutputTokens**: Controls the maximum number of tokens in the generated text (default: `8192`)
- **responseMimeType**: Controls the format of the generated text (default: `"text/plain"`)

## Example Use Cases

- Building a chatbot for customer support
- Generating text for content creation
- Creating a conversational interface for a web application

## API Documentation

The `run` function takes a single argument, `prompt`, which is the input text for the conversational AI model. The function returns a promise that resolves to the response from the model as a string.

## Troubleshooting

- Make sure to replace `Your API Key` with your actual Google Cloud API key.
- Check the console output for any error messages.
- Consult the [Google Generative AI API documentation](https://cloud.google.com/generative-ai) for more information on error handling and troubleshooting.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.
