# Vortex Tech — App Development Internship (Week 1)

## 📱 Project: Static Login Screen UI

This repository contains my submission for **Week 1 (Beginner)** of the Vortex Tech
App Development Internship track. The goal of this task was to get comfortable with
Flutter fundamentals by building a single, well-structured static UI screen — no
logic or interactivity yet, just clean layout and visual structure.

---

## 🎯 Objective

Build a static mobile UI screen using Flutter with proper widget structure
(`Column`, `Row`, `Container`, `Padding`) instead of absolute positioning, ensuring
the layout looks correctly proportioned on a standard mobile screen size.

---

## ✨ What I Built

I chose to build a **Login Screen**, a common and practical UI pattern for
beginners to practice layout and spacing. The screen includes:

| Element | Description |
|---|---|
| 🔒 Icon/Logo | A circular icon at the top acting as a placeholder app logo |
| 📝 Welcome Text | A bold heading ("Welcome Back") with a short subtext |
| 📧 Email Field | A `TextField` with a prefix icon and rounded border |
| 🔑 Password Field | A `TextField` with `obscureText: true` and a lock icon |
| 🔗 Forgot Password | A right-aligned `TextButton` link |
| 🔘 Login Button | A styled `ElevatedButton` with rounded corners |
| 👤 Sign Up Row | A `Row` combining plain text and a tappable "Sign Up" link |

That's 7 distinct UI elements in total — more than the minimum 5 required by the
task brief.

---

## 🛠️ Tech Stack

- **Framework:** Flutter
- **Language:** Dart
- **Widgets used:** `Scaffold`, `SafeArea`, `Center`, `SingleChildScrollView`,
  `Column`, `Row`, `Container`, `TextField`, `ElevatedButton`, `TextButton`,
  `GestureDetector`, `SizedBox`, `Padding`

No external state management or backend — this is a purely static UI screen, as
required for Week 1.

---

## 📐 Layout Approach

Instead of positioning elements with fixed pixel coordinates, the entire screen
is built using Flutter's layout system:

- A `Column` acts as the main vertical container, holding every element in order
  from top to bottom.
- `SizedBox` widgets control consistent vertical spacing between sections.
- The whole `Column` is wrapped in a `SingleChildScrollView` so the layout
  doesn't overflow on smaller screens, and a `Center` + `SafeArea` combo keeps
  everything properly positioned across different device sizes.
- `TextField`s use `InputDecoration` with rounded borders and fill color for a
  clean, modern look rather than the default Material underline style.

---

## 🚀 How to Run This Project

1. **Install Flutter** (if you haven't already) by following the
   [official guide](https://docs.flutter.dev/get-started/install).

2. **Verify your setup:**
   ```bash
   flutter doctor
   ```

3. **Clone this repository:**
   ```bash
   git clone <your-repo-url>
   cd vortextech-appdev-week1
   ```

4. **Install dependencies:**
   ```bash
   flutter pub get
   ```

5. **Run the app** on an emulator or a connected physical device:
   ```bash
   flutter run
   ```

---

## 📂 Project Structure

```
vortextech-appdev-week1/
├── lib/
│   └── main.dart        # App entry point + LoginScreen widget
├── pubspec.yaml          # Project dependencies and configuration
└── README.md             # This file
```

---

## 📚 What I Learned

- How Flutter's widget tree and layout system work compared to absolute
  positioning in plain XML/HTML.
- The difference between `Column`/`Row` for structure and `Padding`/`SizedBox`
  for spacing.
- How to style `TextField`s and buttons using `InputDecoration` and
  `ElevatedButton.styleFrom` for a more polished look.
- Setting up and running a Flutter project end-to-end, from `flutter create`
  to testing on an emulator.

---

## 🔖 Submission Info

- **Internship:** Vortex Tech — App Development Track
- **Week:** 1 of 4 (Beginner)
- **Track:** App Development
- **Author:** Muhammad Daud

---

*This project was built as part of the Vortex Tech Internship Program 2026.*
