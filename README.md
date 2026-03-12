<div align="center">

<img src="https://img.shields.io/badge/version-1.0.0-6366F1?style=for-the-badge&labelColor=0F172A" />
<img src="https://img.shields.io/badge/platform-Android%20%7C%20iOS%20%7C%20Web-7C3AED?style=for-the-badge&labelColor=0F172A" />
<img src="https://img.shields.io/badge/built%20with-React%20Native-61DAFB?style=for-the-badge&labelColor=0F172A" />
<img src="https://img.shields.io/badge/license-MIT-FBBF24?style=for-the-badge&labelColor=0F172A" />

<br />
<br />

```
  ____  _             _       ____
 / ___|| |_ _   _  __| |_   _/ ___| _   _ _ __   ___
 \___ \| __| | | |/ _` | | | \___ \| | | | '_ \ / __|
  ___) | |_| |_| | (_| | |_| |___) | |_| | | | | (__
 |____/ \__|\__,_|\__,_|\__, |____/ \__, |_| |_|\___|
                         |___/       |___/
```

### 📚 Your All-in-One Study & Productivity Companion

*Track your day. Crush your goals. Master your syllabus. Build streaks that last.*

<br />

[**⬇️ Download APK**](https://drive.google.com/file/d/1dhf1iPpd4oWbP61qtdP5ZgkWOWDWADfC/view?usp=sharing) · [**✨ Features**](#-features) · [**🛠 Tech Stack**](#-tech-stack) · [**🚀 Getting Started**](#-getting-started)

<br />

---

</div>

## 🧠 What is StudySync?

**StudySync** is a cross-platform productivity and study app built for students and self-learners who want to do more than just take notes. It combines daily habit tracking, task management, quiz generation, syllabus planning, goal setting, and detailed progress statistics — all in one clean, fast app.

No more switching between 5 different apps. StudySync brings everything together.

> *Plan your day. Convert your syllabus into a schedule. Make quizzes from your notes. Track your streaks. See your progress week by week.*

---

## ✨ Features

### 📅 Daily Activity Tracker
- Log your daily study and productivity activities
- See exactly how you spent your day
- Visual timeline of completed and pending tasks
- Daily summary at end of day
- Colour coded by activity type

### ✅ Todo List
- Simple fast task creation
- Priority levels — high, medium, low
- Due dates and reminders
- Subtasks within each task
- Swipe to complete or delete
- Categorise by subject or project

### 🧩 Quiz Maker
- Create custom quizzes from your own notes or syllabus
- Multiple choice, true/false, and short answer formats
- Timed quiz mode
- Score tracking and review of wrong answers
- Repeat missed questions automatically
- Share quizzes with friends

### 📖 Syllabus Converter
- Paste or upload your syllabus
- App converts it into a structured study schedule automatically
- Assign topics to specific days or weeks
- Mark topics as done as you study
- See percentage completion per subject
- Adjust schedule if you fall behind

### 🎯 Goal Tracker
- Set short term and long term goals
- Break goals into milestones
- Track progress visually with progress bars
- Daily nudges to keep you on track
- Celebrate when goals are completed

### 📊 Monthly and Weekly Statistics
- Detailed charts showing study hours per day
- Weekly comparison — this week vs last week
- Monthly overview of productivity score
- Most productive time of day analysis
- Subject wise time distribution
- Streak history calendar

### 🔥 Streak Mode
- Build daily study streaks
- Streak counter visible on home screen
- Freeze streak for one day if you miss (limited uses)
- Weekly and monthly streak milestones
- Motivational notifications to maintain streaks

---

## 🛠 Tech Stack

```
┌──────────────────────────────────────────────┐
│                  StudySync                    │
├──────────────────────────────────────────────┤
│  Framework      │  React Native               │
│  Platform       │  Android · iOS · Web        │
│  Language       │  TypeScript                 │
│  Navigation     │  React Navigation           │
│  State          │  Zustand                    │
│  Local Storage  │  AsyncStorage               │
│  Charts         │  Victory Native             │
│  Notifications  │  Expo Notifications         │
│  Styling        │  NativeWind                 │
└──────────────────────────────────────────────┘
```

---

## 📁 Project Structure

```
studysync/
├── app/
│   ├── (tabs)/
│   │   ├── home.tsx              # Daily activity tracker
│   │   ├── todos.tsx             # Todo list
│   │   ├── quiz.tsx              # Quiz maker
│   │   ├── syllabus.tsx          # Syllabus converter
│   │   ├── goals.tsx             # Goal tracker
│   │   └── stats.tsx             # Statistics
│   └── _layout.tsx
├── components/
│   ├── tracker/
│   ├── todo/
│   ├── quiz/
│   ├── syllabus/
│   ├── goals/
│   ├── stats/
│   ├── streak/
│   └── ui/
├── stores/
│   ├── activityStore.ts
│   ├── todoStore.ts
│   ├── quizStore.ts
│   ├── syllabusStore.ts
│   ├── goalStore.ts
│   └── streakStore.ts
├── hooks/
├── utils/
├── types/
└── assets/
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18 or above
- npm or yarn
- Expo CLI
- Android device or emulator

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/studysync.git
cd studysync

# Install dependencies
npm install
```

### Run the App

```bash
# Start Expo development server
npx expo start

# Run on Android
npx expo run:android

# Run on iOS
npx expo run:ios

# Run on Web
npx expo start --web
```

### Build APK

```bash
# Install EAS CLI
npm install -g eas-cli

# Login to Expo account
eas login

# Build Android APK
eas build --platform android --profile preview
```

---

## 📲 Download

<div align="center">

### Android APK — v1.0.0

[**⬇️ Download StudySync.apk**](https://drive.google.com/file/d/1dhf1iPpd4oWbP61qtdP5ZgkWOWDWADfC/view?usp=sharing)

`v1.0.0 · Android 8.0+`

> ⚠️ Android may show a Play Protect warning because this app is not on the Play Store yet.
> Tap **More details → Install anyway** — completely normal for indie APKs.
> You may need to enable **Settings → Security → Unknown Sources** first.

</div>

---

## 🗺 Roadmap

- [x] Daily activity tracker
- [x] Todo list with priorities and subtasks
- [x] Quiz maker with multiple formats
- [x] Syllabus to schedule converter
- [x] Goal tracker with milestones
- [x] Weekly and monthly statistics
- [x] Streak mode with freeze
- [ ] Cloud sync across devices
- [ ] AI powered quiz generation from notes
- [ ] Google Calendar integration
- [ ] Dark mode
- [ ] Home screen widget for streak
- [ ] iOS App Store release
- [ ] Google Play Store release

---

## 🤝 Contributing

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a new branch — `git checkout -b feature/your-feature`
3. Make your changes
4. Commit — `git commit -m 'Add your feature'`
5. Push — `git push origin feature/your-feature`
6. Open a Pull Request

For bugs please open an issue with your Android version, device model, and a screenshot if possible.

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

**StudySync** — Plan it. Track it. Crush it.

*v1.0.0 · Built with React Native · 2026*

⭐ Star this repo if StudySync helped you stay productive

</div>
