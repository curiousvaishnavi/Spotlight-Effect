# ✨ Spotlight Effect

A simple and interactive **Spotlight Effect** built using **HTML, CSS, and JavaScript**.

The spotlight follows the user's mouse movement and creates a dynamic glowing effect on the webpage. This project demonstrates how the `mousemove` event can be used to create interactive and engaging UI effects.

## 🚀 Live Demo

🔗 [View Live Demo](https://curiousvaishnavi.github.io/Spotlight-Effect/)

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- DOM Manipulation
- `mousemove` Event
- CSS `radial-gradient()`

## ✨ Features

- 🖱️ Interactive mouse-following spotlight
- 💡 Dynamic radial gradient effect
- 🎨 Smooth visual experience
- ⚡ Lightweight and fast
- 📱 Simple and responsive layout
- 🚫 Custom cursor interaction

## 📂 Project Structure


Spotlight-Effect/
│
├── index.html
├── style.css
├── script.js
└── README.md

🧠 How It Works

The project uses JavaScript's mousemove event to detect the position of the mouse.

document.addEventListener("mousemove", function (event) {
    // Get mouse position
    let x = event.clientX;
    let y = event.clientY;
});

The mouse coordinates are then used to update the position of the spotlight effect dynamically.



#Basic Flow


Mouse Movement
      ↓
mousemove Event
      ↓
Get Mouse X and Y Coordinates
      ↓
Update Spotlight Position
      ↓
Display Dynamic Spotlight


📚 What I Learned

While building this project, I learned:

How the mousemove event works
How to access mouse coordinates using clientX and clientY
How to manipulate CSS properties using JavaScript
How radial-gradient() can create a spotlight effect
How to create custom cursor effects
How pointer-events: none works
How JavaScript and CSS can work together to create interactive UI effects


🔮 Future Improvements
Add smoother spotlight animations
Add multiple spotlight effects
Add interactive hover effects
Add dark/light theme support
Improve mobile responsiveness
Add customizable spotlight colors



👩‍💻 Author

Vaishnavi Dethe

Learning and building projects with HTML, CSS, and JavaScript 🚀


⭐ Support

If you found this project interesting, consider giving the repository a ⭐ on GitHub!
