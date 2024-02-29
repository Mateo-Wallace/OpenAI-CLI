[![License Shield](https://img.shields.io/github/license/Mateo-Wallace/OpenAI-CLI.svg?style=for-the-badge)](./LICENSE)
[![Issues Shield](https://img.shields.io/github/issues/Mateo-Wallace/OpenAI-CLI.svg?style=for-the-badge)](https://github.com/Mateo-Wallace/OpenAI-CLI/issues)

# OpenAI CLI

## Description

OpenAI CLI is a command line application that serves as a basic learning practice in using `gpt-3.5-turbo`. The user is able to input a javascript related coding question and receive a response containing example code and an explanation.

### Tech

[![OpenAI](https://img.shields.io/badge/openai-412991?&style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![LangChain](https://img.shields.io/badge/LangChain-1D3C3D?&style=for-the-badge&logo=linkfire&logoColor=white)](https://python.langchain.com/docs/get_started/introduction)
[![Node.js Shield](https://img.shields.io/badge/Node.js-339933?&style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/en/)
[![JavaScript Shield](https://img.shields.io/badge/JavaScript-F7DF1E?&style=for-the-badge&logo=javascript&logoColor=272727)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Installation

OpenAI CLI is a command line application. Therefore you will need to download the project in order to make use of it.

1. Open your terminal and clone the repo

   ```
   SSH:
   git clone git@github.com:Mateo-Wallace/OpenAI-CLI.git

   HTTPS:
   git clone https://github.com/Mateo-Wallace/OpenAI-CLI.git
   ```

2. Install NPM packages

   ```bash
   npm i
   ```

3. Rename the `.env.EXAMPLE` file to `.env` and input your api key from [OpenAI](https://platform.openai.com/docs/overview)

   ```
   OPENAI_API_KEY="MY-API-KEY"
   ```

## Usage

After finishing the [installation instructions](#installation) open your terminal and follow this workflow:

1. Run `npm start`
1. The CLI will respond `Ask a coding question`
1. Enter your question.
   > Example Input: `How do you capitalize all characters of a string`
1. The application will then respond with an object.
   > Example Output:
   >
   > ```json
   > {
   >   "code": "function capitalize(str) { return str.toUpperCase(); }",
   >   "explanation": "The function takes in a string as a parameter and uses the built-in toUpperCase() method to convert all characters to uppercase. This method does not change the original string, but returns a new string with all uppercase characters. The function then returns this new string as the result."
   > }
   > ```

## License

Distributed under the MIT License. See [LICENSE](./LICENSE) for more information.

## Contact

For any further questions feel free to contact via:

- Project Link: [github.com/Mateo-Wallace/OpenAI-CLI](https://github.com/Mateo-Wallace/OpenAI-CLI)

- Mateo Wallace - [GitHub](https://github.com/Mateo-Wallace) - [Email](mailto:mateo.t.wallace@gmail.com) - [LinkedIn](https://www.linkedin.com/in/mateo-wallace-57931b254/)
