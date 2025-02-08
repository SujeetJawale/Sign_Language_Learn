
![BE MY VOICE](https://github.com/user-attachments/assets/5179bcf6-52e8-473e-8619-c34208eefa36)

# Be My Voice 
### Hackathon - [SoCal Tech Week 2024](https://www.socaltechweek.com/)
[DevPost](https://lnkd.in/ducjsZD4)

**Be My Voice** bridges communication gaps with real-time ASL translation, helping individuals with speech disabilities connect, be understood, and confidently pursue their dream careers. We are participating in the **Accessibility Vertical** for SoCal Tech Week 2024. Our mission is to design a program that promotes inclusivity for everyone.



---

## Inspiration

When we saw the Accessibility track, we knew we could make a real difference. Our goal with **Be My Voice** is to break down barriers for individuals with speech disabilities, making communication easier and more inclusive. By providing real-time ASL translation, we empower users to connect, build relationships, and pursue opportunities while sharing their voices with the world.

---

## What It Does

**Be My Voice** has two main features:
1. **Real-time ASL Translation**: Translates American Sign Language gestures into readable text or speech in real-time.
2. **ASL Flashcards**: Interactive flashcards for learning ASL, featuring simple yet universal vocabularies.

We trained a custom model for ASL translation and utilized OpenAI's ChatGPT to enhance the vocabulary and context-based understanding.

---

## How We Built It

Our tech stack includes:
- **Frontend**: JavaScript (with Bootstrap for UI customization)
- **Middleware API**: Flask
- **Backend**: Python (with OpenCV, MediaPipe, and TensorFlow for computer vision)

Steps:
1. Trained a model with hundreds of images symbolizing ASL vocabularies using Python's TensorFlow.
2. Expanded vocabulary context using OpenAI's ChatGPT for better understanding.
3. Bridged the Frontend and Backend using Flask for real-time computations.
4. Designed an intuitive UI with Bootstrap to enhance user experience.

---

## Challenges We Faced

- **Multi-platform Complexity**: Originally aimed for React Native for cross-platform use but limited by time.
- **Dataset Limitations**: Creating a custom dataset for ASL vocabularies was time-intensive and required extensive manual effort.
- **Hardware Constraints**: Training non-static, time-series ASL gestures on limited hardware was computationally intensive, leading to multiple system crashes.

---

## Accomplishments

- Trained a functional ASL model with acceptable accuracy despite time and hardware constraints.
- Built an end-to-end solution integrating frontend, middleware, and backend seamlessly.
- Created a user-friendly interface with Bootstrap for inclusivity and accessibility.

---

## What We Learned

- American Sign Language is more complex than anticipated, particularly for non-static or niche vocabulary.
- Training time-series models for ASL gestures requires advanced computational resources.
- Collaborative problem-solving and rapid iteration are critical for meeting deadlines in hackathons.

---

## What's Next for Be My Voice

- Enhance the ASL model for non-static gestures with better hardware.
- Expand the dataset to include niche and trendy vocabulary.
- Explore deploying the solution on mobile platforms to reach a wider audience.
- Continue learning about ASL and developing innovative solutions in accessibility.

---

## Built With

- **Frontend**: JavaScript, Bootstrap
- **Middleware**: Flask
- **Backend**: Python, OpenCV, MediaPipe, TensorFlow
- **AI/ML**: OpenAI's ChatGPT, TensorFlow

