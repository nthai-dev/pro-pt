**AI Gym App: Complete Design Summary**

---

### 🔍 Project Overview

An AI-powered mobile gym app that allows users to plan, track, and improve their fitness through intelligent assistants, daily logs, and camera-based pose detection. Core modules include workout planning, nutrition logging, BMI tracking, and AI guidance.

---

### 🔧 Core Requirements

1. **Body Tracker**

   - Input height/weight to calculate BMI
   - Visualize BMI trends
   - Upload and compare progress images

2. **Workout Plan Manager**

   - Create and customize workout plans
   - Log daily workouts from a plan or freestyle
   - Add, edit, and track sets/reps/weight
   - Browse exercise library and save history

3. **Nutrition Tracker**

   - Log daily meals and macros (protein, carbs, fat, calories)
   - Monitor macro goals
   - Quick-add from meal library or manual entry

4. **AI Assistant**

   - Voice command input (e.g., "Start leg day")
   - AI chat Q&A for fitness tips
   - Pose detection via phone camera with real-time feedback

5. **User Profile**

   - Set fitness goals and preferences
   - Customize units and assistant settings
   - Manage personal data and logout

---

### 🔹 Site Map & Navigation Flow

```
[Launch Screen]
     |
     v
[Login / Register] ---> [Forgot Password]
     |
     v
[Home Dashboard]
     |
     |---> [Workout Module]
     |         |---> [Plan Manager]
     |         |---> [Current Workout]
     |         |---> [Exercise Library]
     |         |---> [Workout History]
     |
     |---> [Nutrition Module]
     |         |---> [Today’s Macros]
     |         |---> [Meal Log]
     |         |---> [Meal Library]
     |         |---> [Nutrition History]
     |
     |---> [Body Tracker]
     |         |---> [BMI Input]
     |         |---> [BMI History]
     |         |---> [Upload Image]
     |
     |---> [AI Assistant]
     |         |---> [Voice Commands]
     |         |---> [Chat Q&A]
     |         |---> [Pose Checker]
     |
     |---> [Profile]
               |---> [User Info]
               |---> [Fitness Goals]
               |---> [Preferences]
               |---> [Account Settings]
               |---> [Logout]
```

---

### 🔢 Page Descriptions (Top to Bottom Layouts)

#### 🏠 Home Dashboard

- Header: App title, voice icon
- Greeting + motivational quote
- Today’s Summary (Workout, Nutrition, BMI)
- Quick Actions: +Workout, +Meal, Pose Check
- Progress Snapshots (charts, bars)
- AI Tips
- Bottom Nav Bar

#### 💪 Workout Page (Plan Manager)

- Header: "Workout", +Add Exercise icon
- **Plan Manager**:
  - List of user plans with Start/Edit/Delete
- **Current Workout**:
  - From plan or single exercise
  - Set rows: [Set #] [Reps] [Weight] [✓]
  - +Add Set, +Add Exercise, Finish Workout
- **Exercise Library**:
  - Search bar, categories, add to plan/log
- **Workout History**:
  - Calendar/log view with stats
- Bottom Nav Bar

#### 🍽️ Nutrition Page

- Header: "Nutrition", +Add Meal icon
- **Today’s Macros**:
  - Bars for calories/protein/carbs/fat
- **Meal Log**:
  - Meals by type with macro details
  - Edit/Delete
- **Add Meal**:
  - Manual input form or saved meal quick-add
- **Meal Library** (optional):
  - Recent or favorite meals
- **Summary/Tips**: AI comment on progress
- Bottom Nav Bar

#### 🧕 AI Assistant Page

- Header: "AI Assistant"
- **Voice Input**: Activate mic
- **Chat Interface**: Ask questions, get fitness/diet answers
- **Pose Checker**:
  - Camera view + overlay feedback
  - Detects form mistakes, gives tips

#### 👤 Profile Page

- Header: "Profile"
- **User Info**: Avatar, name, email, Edit Profile
- **Fitness Goals**:
  - Target BMI, weight, macro goals
- **Preferences**:
  - Units, default views, assistant toggles
- **Account Settings**: Password, privacy, export data
- **Logout/Delete Account**
- Bottom Nav Bar

---

### 📊 MVP Focus

- Logging: Workout, meals, BMI
- AI Assistant: Voice + chat Q&A
- Camera: Pose feedback for basic exercises

---

### 🔧 Suggested Tech Stack

| Component       | Tool / Service                  |
| --------------- | ------------------------------- |
| Frontend        | React Native (Expo)             |
| Backend         | Firebase (Auth, Firestore)      |
| Voice Assistant | Google Speech-to-Text / Whisper |
| AI Chat         | OpenAI GPT-4 API                |
| Pose Detection  | MediaPipe / TensorFlow Lite     |
| Image Storage   | Firebase Storage / Cloudinary   |

---

Let me know if you want this exported as a PDF, turned into wireframes, or formatted as a pitch or PRD (Product Requirements Document).

add the MVP plan

