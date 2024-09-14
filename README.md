## Startup: *`Linguamaps`*

<div style="display: flex; justify-content: center;">
    <img src="assets/Logo.gif" alt="Logo GIF" style="width: 200px; height: auto;">
</div>

### Elevator Pitch

**Linguamaps** is a revolutionary web application that transforms the way we learn languages by using *AI* to deliver a <u> personalized, immersive, and cost-effective learning experience</u>.<br>By integrating real-world scenarios with interactive exercises on a *Google Maps* Street View interface, **Linguamaps** offers users a practical approach to mastering new languages.<br> It's designed to address the limitations of <u>traditional language learning tools</u> by providing progressive language practice ~~without the need for gamification~~, making language learning ``accessible and effective`` for everyone.
<div style="text-align: center;">

![Language Overview](assets/LangaugeOverview.jpg)

</div>

### Key Features

**`AI-Driven Language Learning`:** Personalized *learning experiences* that adapt to the user's language level and progress.<br>
**`Real-World Practice`:** Engage with practical scenarios like ordering food, asking for directions, or conversing in daily situations.<br>
**`Progressive Learning Path`:** Start with simple phrases and gradually move to more complex sentence structures as proficiency improves.<br>
**`Minimalistic Progress Tracking`:** Receive constructive feedback and progress reports focused on mastering language skills without gamification distractions.<br>
**`Seamless Interface`:** Utilizes Google Maps Street View for an immersive learning environment, simulating real-life conversations without game-like elements.<br>

<div style="text-align: center;">
    ---------------------------------------------
</div>

### Technologies overview:  *`Linguamaps`*
At this project, we will be utilizing the following technologies:<br><br>
| Feature                  | Description                                                                                                        |
|--------------------------|--------------------------------------------------------------------------------------------------------------------|
| **HTML**                 | Uses correct HTML structure for the application, with pages for login, main interface, and progress tracking.     |
| **CSS**                  | Styling for responsive design, good use of whitespace, and consistent color schemes across devices.                |
| **JavaScript**           | Handles user interactions, such as selecting languages, navigating through exercises, and rendering feedback.      |
| **React**                | Utilizes React for building a single-page application with component-based structure, routing, and state management.|
| **Service**              | Backend service with endpoints for:<br> - `login`: Handles user authentication and session management.<br> - `retrieveExercises`: Fetches personalized language exercises.<br> - `submitProgress`: Submits user progress for tracking and feedback.|
| **Third-Party Service**  | Integration with Google Maps API for Street View and OpenAI API for generating dialogue prompts.                   |
| **DB/Login**             | Uses a secure database to store user profiles, progress data, and credentials. Ensures that users are authenticated before accessing learning features. |
| **WebSocket**            | Enables real-time updates and interactions, such as immediate feedback on exercises and collaborative practice with other users. |
___
<br><br>
<div style="text-align: center;">

🌟 **`Linguamaps`** Design 🌟 
</div>

Below are rough sketches of the application's layout:<br>

**Main Interface Layout**: Features a Google Maps Street View, language selection dropdowns, and interactive dialogue prompts.

![Main Interface Sketch]()

**Progress Report Page**: A minimalistic display of progress tracking, feedback on areas of improvement, and next steps for learning.

![Progress Report Sketch]()
___