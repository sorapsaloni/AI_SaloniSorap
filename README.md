# AI_SaloniSorap
Students struggle to learn from scattered resources, while videos are time-consuming and lack personalization. This project uses AI + Manim to auto-generate educational videos, directly extracting knowledge from textbooks for reliable, efficient, and accurate learning.
AI-Powered Knowledge Graph to Manim Animation Automation

=> **Problem Understanding**
Students often struggle to learn from scattered resources, while videos are time-consuming and lack personalization.
This project uses AI + Manim to automatically generate educational videos. Unlike random online resources, the system extracts knowledge directly from textbooks, making the content reliable, efficient, and accurate for students.

=> **Solution Approach**

The solution works as a pipeline:

- Knowledge Graph → Stores textbook content for easy concept retrieval.

- AI Module → Generates explanations, slides, and scripts.

- Formatter → Structures AI output into clear lessons.

- Manim Automation → Converts the script into animated videos.

- Backend Orchestration → Connects all modules.

- Storage System → Saves and retrieves videos for reuse.

=> **Trade-offs & Thought Process**

- Accuracy vs Speed → Chose textbook-based Knowledge Graph for reliability.

- Animation Quality → Manim provides clarity but requires more rendering time.

- Scalability → Prototype focuses on limited domains first.

- Privacy vs Accessibility → Only educational content, no personal data stored.

=> **Future Improvements**

- Add AI voice-over narration for natural explanations.

- Support multi-language videos for global reach.

- Personalize difficulty (beginner, intermediate, expert).

- Real-time Q&A chatbot linked to Knowledge Graph.
