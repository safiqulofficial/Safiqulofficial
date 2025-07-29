## Hi there 👋

<!--
**safiqulofficial/Safiqulofficial** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->



# Website Code for SafiqulSite

Here is the full source code of my website.

---

### 📄 index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Safiqul Official Site</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Welcome to Safiqul’s Official Website</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>Hello! I'm Safiqul Islam, a passionate creator, writer, and thinker. Welcome to my personal space on the internet.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <ul>
        <li>Poetry Collection</li>
        <li>AI & Philosophy Blog</li>
        <li>Future Visions Book</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: safiqulofficial@example.com</p>
    </section>
  </main>

  <footer>
    <p>© 2025 Safiqul Islam. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>




/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background-color: #f5f5f5;
  color: #333;
  padding: 20px;
}

/* Header */
header {
  background-color: #004466;
  color: #fff;
  padding: 20px;
  text-align: center;
  border-radius: 10px;
}

header h1 {
  font-size: 2.2rem;
  margin-bottom: 10px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 12px;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

/*
# 🌐 SafiqulSite

Welcome to my official website built with HTML, CSS, and JavaScript. This README shows the full source code.

---

## 📄 index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Safiqul Official Site</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Welcome to Safiqul’s Official Website</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>Hello! I'm Safiqul Islam, a passionate creator, writer, and thinker. Welcome to my personal space on the internet.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <ul>
        <li>Poetry Collection</li>
        <li>AI & Philosophy Blog</li>
        <li>Future Visions Book</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: safiqulofficial@example.com</p>
    </section>
  </main>

  <footer>
    <p>© 2025 Safiqul Islam. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
```

---

## 🎨 style.css

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background-color: #f5f5f5;
  color: #333;
  padding: 20px;
}

header {
  background-color: #004466;
  color: #fff;
  padding: 20px;
  text-align: center;
  border-radius: 10px;
}

header h1 {
  font-size: 2.2rem;
  margin-bottom: 10px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 12px;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

main {
  margin-top: 30px;
}

section {
  background: #fff;
  margin-bottom: 20px;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
}

section h2 {
  margin-bottom: 10px;
  color: #004466;
}

footer {
  margin-top: 30px;
  padding: 15px;
  text-align: center;
  background-color: #222;
  color: #eee;
  border-radius: 10px;
}
```

---

## 🧠 script.js

```javascript
// Scroll smoothly to sections when nav links are clicked
document.querySelectorAll("nav a").forEach(link => {
  link.addEventListener("click", function(e) {
    e.preventDefault();
    const targetId = this.getAttribute("href").substring(1);
    const targetElement = document.getElementById(targetId);
    if (targetElement) {
      targetElement.scrollIntoView({ behavior: "smooth" });
    }
  });
});

// Optional: Show alert on page load
window.addEventListener("load", () => {
  console.log("Welcome to Safiqul's Site!");
});
```

---

## 🔗 Live Website (Optional)
Once deployed, the site will be available at:

```
https://your-username.github.io/SafiqulSite/
```

---

## 📬 Contact
If you love the work or have suggestions:

**Email:** safiqulofficial@example.com  
**YouTube:** [Your Channel Link]  
**Instagram:** [@yourhandle]

---
