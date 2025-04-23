# 🍕 FullstackPizza

**FullstackPizza** is a static web application showcasing modern frontend development and clean UI design. Built with responsive layouts and deployed in a production environment, it's served under a subpath on my portfolio domain.

TThis project demonstrates static site hosting from the droplet's file system, reverse proxied via Caddy.

---

## 🧠 Overview

- Built as a static website (HTML, CSS, JS)
- Responsive layout with a pizza-themed UI
- Served directly from the Droplet file system (no Docker)
- Reverse proxied by Caddy under a custom subpath
- Hosted at: [https://chrisimbolon.dev/fullstack-pizza](https://chrisimbolon.dev/fullstack-pizza)

---

## 🎨 Features

- Clean UI and custom pizza-themed design
- Fully responsive layout
- Mobile-first experience
- No backend required

---

## 🐳 Local Development

To run this project locally using Docker:

```bash
git clone https://github.com/chrisimbolon/fullstack-pizza.git
cd fullstack-pizza
```

Visit [http://localhost:3005](http://localhost:3005) to see it in action.

---

## 🔄 Production Deployment

This static site is deployed directly to the **DigitalOcean Droplet**:

- Files are placed in `/var/www/fullstack-pizza`
- Caddy is configured to reverse proxy requests from `/fullstack-pizza` to this directory
- No containerization or server-side logic is required

To update the site:
1. Replace or update the contents of `/var/www/fullstack-pizza`
2. Reload or restart the Caddy container if needed


## 📁 Project Structure

```
fullstack-pizza/
├── css/             
├── fonts/
├── img/
├── js/
└── index.html

```

---

## 🙋‍♂️ Author

**Christyan Simbolon**  
🌐 [Portfolio](https://chrisimbolon.dev)  
💻 [GitHub](https://github.com/chrisimbolon)  
🔗 [LinkedIn](https://linkedin.com/in/christyan-simbolon-60a854360)


