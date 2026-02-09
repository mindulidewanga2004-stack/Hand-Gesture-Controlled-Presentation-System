# Hand-Gesture-Controlled-Presentation-System
✋ Hand Gesture Controlled Presentation System
  This project explores how hand gestures can replace traditional presentation tools by using real-time computer vision. Instead of clicking a mouse or holding a remote,       presentations can be controlled naturally using hand movements in front of a webcam.
  The system detects a single hand, understands finger positions, and translates them into actions such as changing slides, pointing at content, drawing annotations, and erasing   them — all in real time.
  It’s designed to feel intuitive, responsive, and interactive, making presentations more engaging and hands-free.
🧠 Project Overview
  Using a webcam feed, the application continuously tracks hand landmarks and identifies specific gestures based on finger states. Each gesture is mapped to a presentation control   action, allowing smooth slide navigation and on-screen interaction.
  A live camera feed is displayed alongside the slides, while annotations appear directly on the presentation, creating an experience similar to a virtual whiteboard.
  This project demonstrates how computer vision can be used to build natural human–computer interaction systems without additional hardware.
✨ Key Capabilities
  Control presentation slides using simple hand gestures
  Navigate forward and backward without touching the keyboard
  Use your finger as a virtual laser pointer
  Draw and annotate directly on slides
  Erase annotations with a gesture
  View real-time webcam feed integrated with slides
🛠 Technologies Used
  The project is implemented entirely in Python and makes use of powerful computer vision libraries:
  OpenCV for video processing and display
  MediaPipe for accurate hand landmark detection
  CVZone for simplified hand tracking utilities
  NumPy for coordinate and data handling
⚙️ How It Works (Conceptually)
  The webcam captures video frames, which are processed to detect hand landmarks.
  Based on the position and state of fingers, gestures are identified and mapped to presentation commands.
  Slides are displayed as images, and annotations are drawn dynamically based on finger movement.
  The system runs fully in real time, providing immediate visual feedback for each gesture.
🎯 Purpose & Learning Outcomes
  This project was built to explore:
  Real-time computer vision applications
  Gesture-based interaction design
  Practical use of hand landmark detection
  Building interactive systems using AI tools
  It highlights how everyday tasks like presentations can be enhanced using vision-based interfaces.
🔮 Future Enhancements
  Support for PDF and PowerPoint files
  Gesture customization options
  Improved gesture stability and accuracy
  Voice feedback or audio cues
  Multi-hand support
👩‍💻 Author
Dewanga Minduli
Undergraduate | Passionate about AI, Computer Vision & Interactive Systems
