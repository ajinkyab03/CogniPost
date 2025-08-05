# CogniPost 🎯

CogniPost is a real-time webcam-based student monitoring system focused on posture detection, blink detection, and focus tracking. It is designed to help users maintain proper focus and posture during screen time, especially useful for students and remote workers.

## 🚀 Features

- 🎥 Real-time webcam integration for posture and blink detection.
- 🧠 Detects:
  - Good/Bad Posture
  - Eye blinks
  - Focus percentage over time
- 📊 Logs:
  - Start/Stop webcam session timestamps
  - Blink count
  - Focus percentage
  - Posture history
- 🗂️ Data stored in MongoDB per user session.
- 🖼️ Snapshot uploads via `Multer` middleware.
- 📈 Dynamic UI updates with focus charts (React).
- 🧾 Personalized dashboard after login with session history.

---

## 🧰 Tech Stack

| Frontend | Backend | Database | Other Tools |
|----------|---------|----------|-------------|
| React.js | Node.js (Express) | MongoDB (Mongoose) | Multer, MediaPipe, OpenCV |

---

## 📦 Installation Steps

```bash
# Clone the repository
git clone https://github.com/your-username/CogniPost.git
cd CogniPost

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
