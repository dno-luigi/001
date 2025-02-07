# level-zero
accessible-ai-4-everyone
# a new way to learn 
Every legend has an origin story. What will yours be?
This project provides a powerful and adaptable introduction into ai, prioritizing accessibility and affordability. Unlike expensive subscription services, lv0 AI Voice Chatbot offers a free and open-source alternative, empowering anyone learn about and utilize (ai) LLMs without significant financial barriers. I don't believe that ai could ever replace us (humans), but I think those who fail to adopt and adapt to ai integration may be left behind. This project ensures everyone that opportunity. 
## Project Status: Alpha - UI & Multi-LLM Focused
This project is currently in the alpha stage, with a strong emphasis on UI development, voice interaction, and multi-LLM support. Core UI functionality is implemented, including a user-friendly interface for voice input and output, along with free speech-to-text and text-to-speech capabilities using the webkit Speech API.  The project already supports multiple LLMs from various APIs. Future development will focus on expanding memory capabilities and integrating advanced features while maintaining accessibility and affordability.
## Our Journey: From Single File to Sophisticated AI
This project began as a simple `index.html` file. Through iterative development and the invaluable assistance of blackboxai, cercebus coder, bolt.diy (ottodev), cline, and countless other ai resources, it has evolved into a more structured application with a focus on a robust and user-friendly voice interface and multi-LLM support. This journey highlights the power of open-source collaboration and the accessibility of AI development. Key technologies leveraged include free and open-source tools like Tailwind CSS and the webkit Speech API.
**Key Milestones:**
   **Initial Concept:** A basic chatbot with text-based input and output.
*   **Interface Enhancement:** A significant redesign of the user interface, focusing on voice interaction and a cleaner, more intuitive design.
*   **Free STT/TTS Integration:** Implementation of free speech-to-text and text-to-speech capabilities using the webkitSpeechRecognition, removing the need for paid subscriptions.
*   **Multi-LLM Support (In Progress):**  Implementation of support for multiple LLMs from various APIs.
## Roadmap
This roadmap outlines the planned development stages for the project.
### Phase 1: UI Development, Multi-LLM Support, and Refinement (In Progress)
*   **UI Enhancements:** Continue refining the user interface, focusing on a seamless voice interaction experience. Add features such as a clear screen button, delete past conversations, customizable UI colors, improved button tooltips, and a file upload function.
*   **Refactor Codebase:** Refactor the codebase to separate HTML, CSS (Tailwind CSS), and JavaScript into distinct files. Implement a JavaScript hub to organize functions and improve maintainability.
*   **Read Aloud Function:** Implement a read-aloud function for AI responses, allowing users to selectively listen to parts of the output.
*   **Multi-LLM Support:** Continue developing and refining the multi-LLM support, allowing users to easily select different LLMs and API providers.
*   **Testing:** Implement unit tests for core UI functionality, voice features, and multi-LLM support.
### Phase 2: Memory Implementation (Planned)
*   **Working Memory:** Implement working memory using a simple list to store conversation history.
*   **Episodic Memory:** Implement episodic memory using Weaviate for storage and retrieval of conversations, along with LangChain for creating reflection summaries. Hybrid semantic and BM25 search will be used for retrieval.
*   **Semantic Memory:** Implement semantic memory using a database or knowledge graph to store and retrieve factual information. Explore cost-effective options like free-tier databases.
*   **Advanced Procedural Memory:** Implement more advanced procedural memory techniques, such as skill composition and reinforcement learning.
### Phase 3: Advanced Features and Scalability (Planned)
*   **LiveKit Integration (Future):** Explore integrating LiveKit for real-time speech-to-text and text-to-speech, considering cost implications. This might be optional if local TTS proves sufficient.
*   **RAG Memory Optimization:** Optimize RAG memory retrieval and storage for improved performance and scalability.
*   **Deployment:** Deploy the application to a cost-effective cloud platform (e.g., Netlify, Vercel, or explore free-tier options).
### Phase 4: Long-Term Vision (Future)
*   **Adaptive Memory:** Implement a more sophisticated adaptive memory system, potentially using techniques like retrieval-augmented generation (RAG) with external knowledge bases.
*   **Advanced UI:** Develop a more sophisticated and user-friendly UI.
*   **Community Contributions:** Encourage community contributions and collaboration.
## Contributing
Contributions are welcome! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for details.
## License
[MIT License](LICENSE)
