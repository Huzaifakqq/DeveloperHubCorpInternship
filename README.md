# Flutter Developers Internship - Cycle 2

## Week 4: API Integration and Networking
**Deadline:** 28th April, 2026  
**Developer:** Huzaifa Kashif

---

## 📝 Project Overview
This project focuses on fetching and displaying data from a RESTful API using the `http` package in Flutter. It demonstrates the ability to handle network requests, parse JSON data into Dart models, and manage different UI states (Loading, Success, and Error).

## 🚀 Features
- **REST API Integration:** Utilizes the `http` package to communicate with [JSONPlaceholder](https://jsonplaceholder.typicode.com/).
- **JSON Parsing:** Custom `User` model with factory constructors for efficient data mapping.
- **Dynamic UI:** - `ListView.builder` for efficient scrolling of user data.
  - `FutureBuilder` to manage asynchronous states.
- **Robust Error Handling:** - Implemented custom headers (User-Agent) to bypass `403 Forbidden` errors.
  - Visual error messages for network failures.
- **User Experience:** Includes a `CircularProgressIndicator` during data fetching.

## 🛠️ Tech Stack
- **Framework:** Flutter
- **Language:** Dart
- **Library:** `http`
- **Data Source:** JSONPlaceholder API

## 📸 Screen Breakdown
1. **Loading State:** Displays a spinner while the API call is active.
2. **User List:** Displays a card-based list showing:
   - User Name
   - User Email
   - Profile Picture (Generated via DiceBear/Pravatar API)
3. **Error State:** Displays a centered error message if the request fails.

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/flutter_internship_week4.git](https://github.com/YOUR_USERNAME/flutter_internship_week4.git)