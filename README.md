# Calorie Counter

A simple, responsive web app to help users track daily calorie intake. Built with HTML, CSS, and JavaScript — perfect for learning DOM manipulation and basic state management.

---

## ✅ Features

- Add food items with name and calorie amount
- Edit and delete items
- View total calories for the day
- Persist data in localStorage so items remain between sessions
- Mobile-first, responsive UI

## 🚀 Live (Local) Usage

1. Clone or download the repository:

   git clone <repository-url>

2. Open `index.html` in your browser (no server required):

   - Double-click `index.html` or
   - Serve with a simple static server (optional): `npx http-server` or `python -m http.server`

3. Use the UI to add, edit, and remove calorie entries.

## 🧩 Project Structure

- `index.html` — App markup
- `styles.css` — Styling and responsive layout
- `script.js` — Application logic (DOM manipulation, event handlers, localStorage)
- `README.md` — Project documentation

## 💡 How it works (brief)

- Items are stored in localStorage as JSON. On load, the app reads saved items and displays them.
- Adding an item updates the UI and localStorage; editing or deleting updates both as well.

## 🛠️ Technologies

- Vanilla JavaScript (ES6+)
- HTML5
- CSS3 (Flexbox, responsive design)

## ✍️ Contributing

Contributions are welcome. Simple guidelines:

1. Fork the repo
2. Create a feature branch (`git checkout -b feat/my-feature`)
3. Commit your changes (`git commit -m "feat: add ..."`)
4. Push to your branch and open a Pull Request

## 🧪 Testing

Manual testing via the browser is sufficient for this small app:

- Add, edit and delete items and refresh to ensure persistence
- Try on different screen sizes to verify responsive behavior

## 📋 To-Do / Ideas

- Add daily/weekly charts
- Add user accounts and backend storage
- Add input validation and accessibility improvements

## 📄 License

MIT

---

If you'd like, I can update this README to include screenshots, usage GIFs, or deployment instructions for GitHub Pages — tell me which you'd prefer.