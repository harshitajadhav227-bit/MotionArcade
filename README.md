## 🎮 How to Run the Project

Some dependencies may need to be installed before running the project. If you encounter a missing-module error, install the required package using `pip install package-name`.

### 🐦 1. Flappy Bird — Gesture Control

1. Run the Python script:

   ```bash
   python flappybird.py
   ```

2. Open [Flappy Bird](https://flappybird.io/) in your browser.
3. Move your mouse cursor over the game frame.
4. Use your **right wrist** to control the game through hand gestures.

*Note: The gesture controls can be configured in the source code.*

### 🏃 2. Subway Surfers — Gesture Control

1. Open [Subway Surfers on Poki](https://poki.com/en/g/subway-surfers/).
2. Complete the initial tutorial using your keyboard.
3. Return to your project terminal and run:

   ```bash
   python subwaysurfers.py
   ```

4. Position yourself so that both wrists are visible to the camera and remain near the centre of the camera frame.
5. Control the game using hand movements:

   - ⬆️ **Move your hand up:** Jump
   - ⬇️ **Move your hand down:** Slide
   - ⬅️ **Move your hand left:** Move left
   - ➡️ **Move your hand right:** Move right

*Note: Spacebar functionality is not currently supported. Ensure that the browser game is active while using gesture controls.*

### ⚙️ Requirements

- Python
- TensorFlow Lite / TensorFlow
- OpenCV
- NumPy
- Matplotlib
- PyAutoGUI
- A working webcam

