# Audio Visualizer <img src="https://img.icons8.com/?size=100&id=1893&format=png">

This project is a web-based audio visualiser built using HTML, CSS, and JavaScript. It leverages the Web Audio API to capture and analyze audio input, and the Canvas API to create dynamic and visually appealing representations of the sound.

**Features:**

* **Real-time Audio Visualization:** Responds to audio input from your device's microphone, displaying visualizations in sync with the audio stream.
* **Configurable Visualization Types:** Allows you to visualization styles to personalize the experience. (Implementation details in the code)
* **User-Friendly Input:** Provides clear instructions and intuitive controls for interacting with the audio input and visualization settings.

**Getting Started**

**Prerequisites:**

* A modern web browser that supports the Web Audio API and Canvas API (most recent versions of Chrome, Firefox, Edge, etc.).

**Running the Project:**

1. Clone or download the project repository.
2. Open `index.html` in your web browser.
3. Grant microphone permission when prompted. You should see the audio visualiser and controls displayed.

**Customization:**

The code includes several visualization functions (see `scripts.js`). You can modify these functions and experiment with different visualization techniques to create unique effects.

**Technologies Used:**

* **HTML:** Provides the basic structure of the web page, including elements for the visualization canvas, input controls, and instructions.
* **CSS:** Styles the HTML elements to create a visually appealing interface and position the visualization and controls appropriately.
* **JavaScript:**
    - **Web Audio API:** Enables capturing audio input from the user's microphone, analyzing its frequency spectrum, and extracting relevant data for visualization. (See `scripts.js` for implementation)
    - **Canvas API:** Provides a drawing surface where you can create and manipulate the visual representation of the audio. (See `scripts.js` for implementation)

**Future Enhancements:**

* **Additional Visualization Types:** Implement more visualization options for users to choose from (e.g., bar graphs, wave forms, particle systems).
* **Audio Source Selection:** Allow users to select audio from different sources (e.g., uploaded files, external players).
* **Interaction and Customization:** Enable users to interact with the visualization in real-time, adjusting parameters like color palettes or animation speeds.

**How to Contribute:**

(Provide instructions on how others can contribute to the project, if applicable.)

**Enjoy creating your own mesmerizing audio visualizations!**
