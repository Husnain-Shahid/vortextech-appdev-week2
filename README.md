# VortexTech AppDev - Week 1: Task Manager Application

A clean, dynamic Task Management app built using Flutter. This project demonstrates state management with `StatefulWidget`, handling user inputs, rendering dynamic lists using `ListView.builder`, and interactive UI updates.

Repository Link: [https://github.com/Husnain-Shahid/vortextech-appdev-week1](https://github.com/Husnain-Shahid/vortextech-appdev-week1)

---

## 📱 What Was Built

* **`StatefulWidget` Integration**: Manages runtime state changes as tasks are added, completed, or removed.
* **Input Section**: Uses a `TextField` with `TextEditingController` and an `IconButton` to capture and insert new items.
* **Dynamic Scrollable List**: Built with `ListView.builder` to dynamically render tasks using custom `Task` data models.
* **Interactive Completion Toggle**: Integrated `CheckboxListTile` that triggers `setState()`, applying strike-through styling (`TextDecoration.lineThrough`) on completed tasks.
* **Flexible Task Deletion**: Supports both a trailing delete `IconButton` and swipe-to-delete functionality using `Dismissible`.

---

## 🎨 Design & Theme

* **Primary Theme Accent**: Indigo (`#6366F1`)
* **Background Tone**: Soft Slate (`#F8FAFC`)
* **Card & Input Filling**: Pure White (`#FFFFFF`)
* **Completed Task Style**: Muted Gray (`#94A3B8`) with strike-through line

---

## 🚀 How to Run

### Prerequisites

* [Flutter SDK](https://docs.flutter.dev/get-started/install) installed.
* An active emulator, simulator, or physical device attached.

### Steps to Execute

1. **Clone the repository**
   ```bash
   git clone [https://github.com/Husnain-Shahid/vortextech-appdev-week2.git](https://github.com/Husnain-Shahid/vortextech-appdev-week2.git)
   cd vortextech-appdev-week2
