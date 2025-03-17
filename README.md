# Voxell - Voice AI Assistant🤖
Voxell is an AI-powered Voice Assistant that utilizes both voice and text interaction features. Developed with the LiveKit framework for real-time communication and Ollama/OpenAI models for AI-powered conversation, Voxell offers users a seamless voice assistant experience.

## Features🌟
Voice Interactions: Users can converse with Voxell through voice, and it will process the speech and respond accordingly.
Text Interactions: Users can also chat with Voxell via text.
Real-Time Communication: Integrated with LiveKit for high-quality, low-latency voice communication.
AI-Powered Responses: Voxell uses the power of OpenAI models and Ollama's Mistral model for natural and responsive conversations.

## Pain Points Solved🔧
### The main pain points solved by Voxell include:
Low-Latency Voice Communication: Many voice assistants have delays in response times. By using LiveKit, Voxell ensures smooth, real-time communication.
Seamless AI Interaction: Previous voice assistants often have limited interaction capabilities or focus only on one form of communication (voice or text). Voxell solves this by integrating both text and voice inputs, offering flexible interaction options.
AI Understanding & Response: With Ollama and OpenAI, Voxell provides intelligent, context-aware responses to user queries, improving the user experience compared to simple scripted bots.

### Challenges Faced⚡
Real-Time Voice Processing: Handling real-time communication and processing voice input while ensuring minimal delay was a major challenge.

Solution: I used LiveKit to facilitate real-time voice streaming and integrated Google Speech-to-Text for accurate and quick transcription, allowing the system to process speech faster.
Integrating Multiple APIs: Integrating LiveKit, Ollama, and OpenAI into one seamless flow was complex.

Solution: I built a modular architecture that isolated the interaction layers for voice, text, and AI models. This allowed me to focus on each component individually and ensure smooth data flow between them.
Latency in AI Responses: AI models often take time to generate responses, which could affect the overall user experience.

Solution: I optimized the integration with Ollama for faster inference, and used techniques like caching and parallel processing to reduce the waiting time for the user.
## Future Improvements🚀
Add Personality: Enhance the conversational abilities of Voxell by adding personality and context-based memory to make interactions more natural.
Better Speech-to-Text Accuracy: Improve the transcription accuracy and speed with better models or services.

### Contributions🤝
Feel free to open an issue or pull request if you have suggestions or improvements to make this project even better!

### License📄
This project is licensed under the MIT License – see the LICENSE file for details.

### Contact📬
For any questions, you can reach out to me on LinkedIn or open an issue on the repository.
