# Realtime Voice Interface

The Realtime Voice Interface in PraisonAI provides an interactive, voice-based communication channel with AI models. This interface allows for real-time audio input and output, enabling a more natural and dynamic conversation experience.

## Features

- Real-time voice input processing
- Text-to-speech output for AI responses
- Seamless integration with OpenAI's realtime API
- Support for various AI models
- Persistent conversation history
- Financial data integration with yfinance

## Getting Started

To use the Realtime Voice Interface, follow these steps:

1. Install PraisonAI with the realtime dependencies:
   ```bash
   pip install "praisonai[realtime]"
   ```

2. Set up your OpenAI API key:
   ```bash
   export OPENAI_API_KEY="your-api-key-here"
   ```

3. Launch the Realtime Voice Interface:
   ```bash
   praisonai realtime
   ```

## Usage

Once the interface is launched:

1. Click the microphone button or press 'P' to start voice input.
2. Speak your message or query.
3. The AI will process your input and respond with both text and voice.
4. You can ask for financial data, which will be fetched using yfinance.
5. The conversation history is maintained for context in ongoing discussions.

## Configuration

You can configure various aspects of the Realtime Voice Interface:

- Model selection: Choose different AI models for processing.
- Voice settings: Adjust voice characteristics for the AI's speech output.
- Audio settings: Configure input/output audio formats and quality.

## Troubleshooting

If you encounter issues:

- Ensure your microphone is properly connected and permitted in your browser.
- Check your internet connection for stable real-time communication.
- Verify that your OpenAI API key is correctly set and has the necessary permissions.

For more detailed information and advanced usage, please refer to the [PraisonAI documentation](https://docs.praison.ai).