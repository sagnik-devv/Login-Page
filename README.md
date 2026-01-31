# Flask Login System with Modern UI

A secure and visually appealing authentication system built with **Flask** and **SQLite**. This project features a modern **glassmorphism** user interface with animated backgrounds and fully responsive design.

## 🚀 Features

- **User Authentication**: Secure Login and Registration system.
- **Modern UI/UX**: Custom CSS implementing Glassmorphism and floating animation effects.
- **Database Integration**: SQLite database with SQLAlchemy ORM.
- **Security**: Password hashing using `scrypt` (via Werkzeug) and session management.
- **Flash Messages**: Interactive user feedback for errors and success states.
- **Protected Routes**: Dashboard is accessible only to logged-in users.

## 🛠️ Tech Stack

- **Backend**: Python, Flask, Flask-SQLAlchemy, Flask-Login
- **Frontend**: HTML5, CSS3 (Animations & Glassmorphism)
- **Database**: SQLite

## 📦 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Set up a virtual environment** (Recommended)
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python3 app.py
   # OR
   flask run
   ```

5. **Access the App**
   Open your browser and visit: `http://127.0.0.1:5001` (or port 5000 if using `flask run`)

## 📸 Screenshots

_(Add your screenshots here)_

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.
