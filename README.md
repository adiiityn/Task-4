# Task-4


---

```markdown
# 📱 Responsive Web Page Using CSS Media Queries

## 🧾 Objective
Convert an existing desktop-only web page into a **mobile-friendly layout** using **CSS media queries**.

## 🛠️ Tools Used
- **HTML5**
- **CSS3 with Media Queries**
- **VS Code**
- **Chrome DevTools** for testing responsiveness

## 📄 Project Structure
```

├── index.html
└── style.css

````

## 🧪 Features
- Responsive design that adapts to different screen sizes (desktop, tablet, and mobile)
- Uses `@media` queries to modify layout for screens with a max width of 768px
- Simple flex-based layout that switches from horizontal to vertical stacking on smaller devices

## ✅ How It Works
1. The default layout is for **desktop** users using Flexbox.
2. A media query targets screens with a width of **768px or less**, stacking elements vertically and making them full-width for easier reading on smaller screens.

## 💻 How to Run
1. Clone or download this repository.
2. Open the project folder in **VS Code**.
3. Open `index.html` in a browser (right-click → "Open with Live Server" if installed).
4. Use **Chrome DevTools** (`Ctrl + Shift + M`) to test responsiveness.

## 🧩 Code Highlights

### HTML
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
````

### CSS Media Query

```css
@media (max-width: 768px) {
  main {
    flex-direction: column;
  }

  .sidebar,
  .content {
    width: 100%;
  }
}
```

## 📸 Screenshots

### 🖥️ Desktop View

* Sidebar and content are side-by-side

### 📱 Mobile View

* Sidebar and content stack vertically

## 📚 License

This project is open source and free to use for educational or personal development purposes.

```

---


```
