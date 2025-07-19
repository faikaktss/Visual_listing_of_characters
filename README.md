.# Star Wars Character Viewer

This project is a simple web application that displays a list of **Star Wars** characters. It uses a static dataset and does not rely on any external APIs. The application allows users to filter characters based on their homeworld and toggle the display of the character cards.

## 📁 Project Structure

```
JS-9320P-1/
├── index.html        # Main HTML structure
├── script.js         # JavaScript logic for rendering and filtering
├── json.json         # JSON-formatted character data (also included inline in script.js)
└── .gitattributes
```

## 🚀 Features

- Show/hide all characters using a toggle button.
- Filter characters by their **homeworld** using radio buttons.
- Display character image, name, and homeworld in Bootstrap-styled cards.
- No external API calls—uses static data only.

## 🔧 Technologies Used

- HTML5
- CSS3 (via [Bootstrap 5](https://getbootstrap.com/))
- JavaScript (Vanilla)

## 🔍 How It Works

1. The app loads the character dataset defined inside `script.js`.
2. The `Show characters` button displays or hides the character cards.
3. Radio buttons are dynamically generated based on unique homeworlds.
4. When a homeworld is selected, only characters from that homeworld are displayed.

## 📸 Screenshots

### Folder Structure

![Folder Structure](./images/folder-structure.png)

### App Description

![App Description](./images/description.png)

---

### Sample Character Card Layout

![Card Example](./images/card-example.png)

---

## 📝 Notes

- The characters are stored in an array called `dataArray` inside the `script.js` file.
- The app is fully client-side—no backend or database is required.
- Compatible with all modern browsers.

---

© 2025 Star Wars Viewer Demo — For learning purposes only.
