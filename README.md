# Focusr-Public

**Focusr** is a mobile application designed to assess and improve attention span using neuroscience-backed tasks and machine learning. It provides personalized diagnostics, real-time attention tracking, and actionable insights, making it a powerful tool for students, educators, and individuals seeking to enhance cognitive focus.
** unforunately not disclosing code for project privacy
## Problem

Attention-related issues are on the rise, especially among students and young professionals. Many existing tools for improving focus are either passive (e.g., timers, reminders) or overly reliant on  connectivity. There is a lack of effective, data-driven solutions that can measure and improve attention span over time in a structured and personalized manner.

## Solution

Focusr addresses this problem by combining attention diagnostics with interactive tasks, computer vision, and predictive modeling. It allows users to engage in quick, research-based tasks that monitor focus and track improvements over time—all within a user-friendly and offline-capable environment.

## Features

- **Neuroscience-Based Attention Tests**
  - *Posner Cueing Task with Gaze Tracking*: Measures attentional shift and reflexes using gaze direction.
  - *N-Back Task*: Assesses working memory and sustained attention.
  - *Visual Search Task*: Evaluates selective attention and visual scanning ability.
  - *Continuous Performance Task (CPT)*: Measures vigilance and impulsivity.

- **Progress Tracking**
  - Weekly diagnostic scores and progress reports
  - Predictive models analyze past performance to estimate future improvement

- **Offline Computer Vision**
  - Real-time pupil tracking to detect distraction during tasks
  - Visual cues and performance metrics without requiring internet access

- **AI Chatbot Coach**
  - Integrated assistant for setting focus goals with factual information
  - Provides feedback and motivational support tailored to user performance

- **Secure User System**
  - Firebase-authenticated login and encrypted data storage
  - Password reset and account recovery features included

## Technical Overview

- **Frontend**: Built using FlutterFlow for rapid deployment and cross-platform compatibility
- **Backend**: Firebase Authentication and Firestore for secure data handling
- **Computer Vision**: Offline pupil tracking using a lightweight CV model
- **Machine Learning**: Predictive model trained on historical data to forecast user attention trends
- **AI Assistant**: Knowledge-based chatbot integrated via AWS bedrock

## Inspiration

The idea for Focusr originated from the widespread difficulty students face in maintaining attention, especially in increasingly digital learning environments. The project aims to go beyond passive productivity tools by offering real-time measurement, training, and support based on actual cognitive science.

## Impact

Focusr has been recognized for its innovative approach to cognitive enhancement:
- **Winner** of the Congressional App Challenge
- **International Finalist** at WAICY (World Artificial Intelligence Competition for Youth)
- Presented at education-focused events

## Future Plans

- Integration with wearable devices for more accurate biometric tracking
- Expansion of the attention scoring model with a larger user dataset
- Localization and language support for broader accessibility

---
