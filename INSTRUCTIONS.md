# Physics Explorer App: Setup & Deployment Instructions

This guide explains how to create, run, and deploy the Physics Explorer interactive app using the provided files and technologies.

---

## License & Usage Restrictions

- **Not for Commercial Use:** This project is licensed for non-commercial use only. Commercial use, distribution, or sale is prohibited without explicit written permission.
- **Attribution Required:** If you copy, fork, or use this project in any form, you must clearly acknowledge the original source (Physics Explorer, https://github.com/NCdev2/Physics-Navigator) in your documentation, user interface, and/or derivative works.
- See the LICENSE file for full terms.

---

## 1. Tools & Technologies Used

- **Streamlit**: Python framework for building interactive web apps.
- **Python 3.8+**: Programming language for backend logic.
- **HTML/CSS/JS**: For the original UI prototype (`physics.html`).
- **SVG**: For animated diagrams.
- **Git & GitHub**: Version control and cloud repository.

---

## 2. Project Structure

```
app.py                # Main Streamlit app (Python)
physics.html          # Original HTML/JS prototype (reference)
requirements.txt      # Python dependencies
README.md             # Project overview
```

---

## 3. Setup Steps

### A. Clone the Repository

```
git clone https://github.com/NCdev2/Physics-Navigator.git
cd Physics-Navigator
```

### B. Install Python & Streamlit

1. Ensure Python 3.8+ is installed (`python --version`).
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

### C. Run the App Locally

```
streamlit run app.py
```
- The app will open in your browser at `http://localhost:8501`.

---

## 4. How It Works

- **Sidebar Navigation**: Select main topics and subtopics.
- **Main Area**: Shows explanations and animated SVG diagrams for each concept.
- **Responsive UI**: Works on desktop and mobile.
- **Streamlit-native**: All navigation and content display is handled in Python, not in the HTML iframe.

---

## 5. Deployment

You can deploy this app for free using [Streamlit Community Cloud](https://streamlit.io/cloud):

1. Push your code to a public GitHub repository (already done).
2. Go to https://streamlit.io/cloud and sign in.
3. Click "New app", select your repo and `app.py` as the entry point.
4. Click "Deploy".

---

## 6. Customization & Extension

- To add or edit topics, subtopics, or SVGs, modify the `physics_data` structure in `app.py`.
- For advanced UI, use Streamlit's layout, components, or custom CSS.
- The original `physics.html` is kept for reference and inspiration.

---

## 7. Technologies Summary

- **Streamlit**: https://streamlit.io/
- **Python**: https://python.org/
- **GitHub**: https://github.com/
- **SVG**: https://developer.mozilla.org/en-US/docs/Web/SVG

---

For questions or contributions, see the GitHub repo: https://github.com/NCdev2/Physics-Navigator
