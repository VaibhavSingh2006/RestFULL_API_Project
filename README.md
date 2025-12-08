# 🚀 Quora-Style RESTful Posts API  
A minimal CRUD app built with Node.js, Express, EJS & UUID.

This project allows users to **create, read, update, and delete posts** using clean RESTful routing.  
The UI is built with **EJS templates**, and forms use **method-override** to support PATCH & DELETE requests.

---

## 🌟 Features

- ✏️ **Create Posts** – Add new posts with username & content  
- 📄 **Read Posts** – View all posts or a single post  
- 📝 **Update Posts** – Edit any post using PATCH  
- ❌ **Delete Posts** – Remove posts permanently  
- 🔗 **RESTful Routing** – Clean and predictable API structure  
- 🆔 **UUID-based IDs** – Each post gets a unique ID  
- 🎨 **EJS Templates** – Simple and clean UI  
- 🔧 **Method Override** – Enables PATCH/DELETE in HTML forms  

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Node.js** | JavaScript runtime |
| **Express.js** | Framework for routing & server |
| **EJS** | Frontend template engine |
| **UUID** | Generate unique IDs |
| **Method-Override** | Support REST via forms |
| **CSS** | Frontend styling |

---

## 📂 Project Structure

REST_CLASS/
│── public/
│ └── style.css
│
│── views/
│ ├── index.ejs # List all posts
│ ├── new.ejs # Create post form
│ ├── show.ejs # Show single post
│ ├── edit.ejs # Edit post form
│
│── index.js # Main server file
│── package.json
│── package-lock.json
│── README.md
│── .gitignore

---

## 🔗 RESTful Routes

| Method     | Route             | Description |
|--------|--------|-------------|
| **GET**  | `/posts`          | Show all posts |
| **GET**  | `/posts/new`      | Form to create a post |
| **POST** | `/posts`         | Create a new post |
| **GET**  | `/posts/:id`      | View a single post |
| **GET**  | `/posts/:id/edit` | Edit form for a post |
| **PATCH** | `/posts/:id`    | Update post |
| **DELETE** | `/posts/:id`   | Delete post |

---

---

## 🔗 RESTful Routes

| Method | Route | Description |
|--------|--------|-------------|
| **GET** | `/posts` | Show all posts |
| **GET** | `/posts/new` | Form to create a post |
| **POST** | `/posts` | Create a new post |
| **GET** | `/posts/:id` | View a single post |
| **GET** | `/posts/:id/edit` | Edit form for a post |
| **PATCH** | `/posts/:id` | Update post |
| **DELETE** | `/posts/:id` | Delete post |

---

🧪 Tools for Testing API

Hoppscotch – API testing in browser
Postman    – Alternative testing tool
Browser UI – Built-in EJS pages.

Author.....
Vaibhav Singh.