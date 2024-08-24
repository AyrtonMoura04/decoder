# Text Decoder Project

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=fff)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=fff)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=000)
![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=fff)
![Vercel](https://img.shields.io/badge/-Vercel-000000?logo=vercel&logoColor=fff)

Welcome to the Text Decoder Project! This application allows you to encode and decode text using a custom cipher. The purpose of this project is to enable you to exchange secret messages with others who know the encoding method.

## Live Demo

- **Vercel**: [View on Vercel](https://decoder-o6g11r9ri-ayrtonmoura04s-projects.vercel.app/)
- **GitHub Pages**: [View on GitHub Pages](https://ayrtonmoura04.github.io/decoder/)

## Features

- **Text Encoding**: Convert regular text into encoded text using a specific set of rules.
- **Text Decoding**: Convert encoded text back into its original form.
- **Input Validation**: Ensures only lowercase letters without accents or special characters are processed.
- **Copy to Clipboard**: Easily copy the encoded/decoded text to your clipboard with a single click.
- **Responsive Design**: The interface is responsive and works well on different screen sizes.

## Encoding Rules

The following rules are used to encode the text:

- `e` becomes `enter`
- `i` becomes `imes`
- `a` becomes `ai`
- `o` becomes `ober`
- `u` becomes `ufat`

For example, the word `gato` would be encoded as `gaitober`, and `gaitober` would be decoded back to `gato`.

## Requirements

- Works only with lowercase letters.
- No accents or special characters allowed.
- The user should be able to:
  - Encode a word to its encoded version.
  - Decode an encoded word back to its original form.

## Installation

To run this project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/AyrtonMoura04/decoder.git
