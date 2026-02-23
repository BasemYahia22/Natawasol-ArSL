# 👐 Natawasol - Arabic Sign Language Translator
# نتواصل - مترجم لغة الإشارة العربية

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-Web-orange.svg)

**Natawasol** is a web-based application designed to bridge the communication gap between the deaf community and Arabic speakers. It utilizes AI to translate Arabic text/audio into Sign Language videos and recognizes Sign Language gestures from the camera into text.

**نتواصل** هو تطبيق ويب يهدف إلى تقريب المسافات بين مجتمع الصم والمتحدثين باللغة العربية. يستخدم الذكاء الاصطناعي لترجمة النصوص والأصوات إلى فيديو بلغة الإشارة، وكذلك التعرف على الإشارات من الكاميرا وتحويلها إلى نص.

## ✨ Features | المميزات

### 1. 🎥 Sign to Text (مترجم 1)
*   **Camera Integration:** Uses the device camera to capture gestures.
*   **Start/Stop Recording:** Control exactly when to capture the sign.
*   **AI Recognition:** Sends video data to the server to recognize Arabic Sign Language gestures.
*   **Real-time Feedback:** Displays the recognized sentence instantly.

### 2. 🗣️ Text/Audio to Sign Video (مترجم 2)
*   **Text Input:** Type Arabic sentences to generate sign language videos.
*   **Voice Input:** Use the microphone to speak, converting speech to text and then to video.
*   **Video Playback:** Automatically plays the generated sign language video with cache-busting integration to ensure fresh content.
*   **TTS (Text-to-Speech):** Converts written text back to spoken audio.

### 3. 🎨 UI/UX
*   **Responsive Design:** Works seamlessly on desktops and mobile devices.
*   **Modern Interface:** Glassmorphism headers, smooth animations, and interactive buttons.
*   **RTL Support:** Fully optimized for Arabic language layout.

## 🛠️ Tech Stack | التقنيات المستخدمة

*   **Frontend:** HTML5, CSS3 (Custom Styles + FontAwesome), JavaScript (ES6+).
*   **APIs:** Custom Genius AI APIs for:
    *   `audio-to-sign`
    *   `text-to-sign`
    *   `recognize` (Video Gesture Recognition)
*   **Libraries:** Native Web APIs (MediaRecorder, SpeechRecognition, SpeechSynthesis).

## 🚀 How to Run | كيفية التشغيل

Since this is a client-side application using vanilla JavaScript, you don't need a complex build process.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YOUR_USERNAME/Natawasol-ArSL.git
    ```
2.  **Open the project:**
    Simply open the `index.html` file in your browser.
    *   *Note: For camera and microphone access to work properly, it's recommended to run this on a local server (like Live Server in VS Code) or via HTTPS.*

## 📸 Usage | طريقة الاستخدام

1.  **Grant Permissions:** Allow camera and microphone access when prompted.
2.  **Choose Mode:**
    *   **Translator 1 (Camera):** Click the "Record" button, perform the sign, then click "Stop". The text will appear in the box.
    *   **Translator 2 (Text/Video):** Type text or record audio, then click "Convert". The sign language video will play below.


## 👨‍💻 Developer

Developed by **Genius AI Team**.
*   **Main Developer:** Basem Yahia Abdel Latif

## 📄 License

This project is licensed under the MIT License.
