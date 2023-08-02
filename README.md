# Joke Teller

Joke Teller is a fun web application that fetches jokes from a joke API and converts them into speech using the VoiceRSS API. Simply press the "Tell Me A Joke" button, and the application will fetch a joke and read it out loud using the voice of "Linda."

## Demo

You can try out the Joke Teller application live [here](https://JSoto56.github.io/joke-teller/).

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Built With](#built-with)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Getting Started

### Prerequisites

To run the Joke Teller application locally, you will need:

- A modern web browser that supports HTML5 and JavaScript.
- An API key for the VoiceRSS API. You can obtain one by signing up on their website [here](https://www.voicerss.org/).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/joke-teller.git
   ```

2. Navigate to the project directory:

   ```bash
   cd joke-teller
   ```

3. Open the `script.js` file and replace `'API_KEY_HERE'` with your actual VoiceRSS API key.

4. Launch the application by opening the `index.html` file in your web browser.

## Usage

1. Click the "Tell Me A Joke" button to fetch a random joke from the joke API.
2. The joke will be read out loud using the voice of "Linda."

## Built With

- [VoiceRSS](https://www.voicerss.org/) - Text-to-Speech API.
- [JokeAPI](https://v2.jokeapi.dev/) - API to fetch jokes.

## Contributing

Contributions are welcome! If you find any issues or have ideas for improvements, please feel free to open an issue or submit a pull request.

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

Please make sure to update tests and documentation as appropriate.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to [VoiceRSS](https://www.voicerss.org/) for providing the Text-to-Speech API.
- Thanks to [JokeAPI](https://v2.jokeapi.dev/) for providing the joke API.

---
