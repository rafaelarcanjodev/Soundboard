# 🔊 Soundboard | Instant Audio Trigger System

![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

A high-performance **Digital Soundboard** designed to enhance the dynamics of live presentations, broadcasts, and podcasts. Inspired by professional radio and TV sound effect systems, this tool provides instant audio feedback with zero-overlap logic.

---

## 🚀 Technical Highlights

* **State Reset Logic:** Implemented a "Reset-before-Play" mechanism using native JavaScript. Each trigger automatically pauses and resets the audio track to `currentTime = 0` before playback. This ensures that rapid, successive clicks result in an instant restart rather than audio overlapping or queuing.
* **Low Latency Interaction:** Optimized event listeners to ensure immediate sound execution, mimicking the responsiveness of professional hardware soundboards.
* **Clean UI/UX:** A grid-based interface built for fast accessibility, allowing the operator to trigger multiple sound effects during live sessions without visual clutter.

## 🛠️ Tech Stack

* **Logic:** Vanilla JavaScript (Native Audio API).
* **Structure:** HTML5 Semantic tags.
* **Styling:** CSS3 (Grid & Flexbox layout).

---

## 🔗 Live Demo

Experience the soundboard in action:  
👉 [**Soundboard Live Preview**](https://rafaelarcanjodev.github.io/Soundboard/)

---

## 🧠 The Engineering Behind the Sound

The core challenge of this project was handling **concurrent triggers**. By leveraging the native `.play()` and `.pause()` methods combined with state resets, the system achieves a "staccato" effect essential for soundboard dynamics. This prevents the common web audio bug where multiple instances of the same sound create a chaotic and non-professional output.

---

## 📩 Contact<br>
Rafael Arcanjo<br>
Backend Software Engineer<br>
[LinkedIn](https://www.linkedin.com/in/rafael-arcanjo-dev) | [GitHub](https://github.com/rafaelarcanjodev)
