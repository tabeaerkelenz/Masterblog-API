# MasterBlog API

A beginner-friendly REST-style blog API built with Flask and vanilla JavaScript.
This project demonstrates client-side rendering (CSR), API design fundamentals, and the separation of frontend and backend in a real-world style architecture.

This was my first backend API project and marks the transition from server-side rendered Flask apps to client-server architecture.

## ✨ Features

- Create new blog posts

- Edit existing posts

- Delete posts

- Retrieve all posts

- Search posts

- Sort posts

- JavaScript frontend consuming a Flask API

- Fully client-side rendered interface (CSR)


## Architecture
```bash
Frontend (HTML/CSS/JS)
        ↓
     Fetch API
        ↓
   Flask REST API
        ↓
  In-memory / JSON-like storage
```


The frontend and backend are decoupled and communicate exclusively through HTTP API calls.

## -> Getting Started
```bash
1. Clone the repository
git clone https://github.com/tabeaerkelenz/Masterblog-API.git
cd Masterblog-API
```

2. Run the backend API
```bash
python app.py
```

The API will start locally (default Flask port).

3. Open the frontend

Open the frontend HTML file in your browser (or serve it via a simple HTTP server).
The frontend will communicate with your local Flask API.

## API Endpoints (Overview)
Method	Endpoint	Description
GET	/posts	Get all posts
GET	/posts/<id>	Get single post
POST	/posts	Create new post
PUT	/posts/<id>	Edit post
DELETE	/posts/<id>	Delete post
GET	/posts/search	Search posts
GET	/posts?sort=...	Sort posts
-> Example Request:
curl http://localhost:5000/posts

Why this project matters

This project represents my first full client-server API, moving away from server-side rendered Flask pages toward a modern API-driven architecture.


## Tech Stack

| Python |

| Flask  |

| HTML   |

| CSS    |

| Vanilla JavaScript |

| Fetch API  |


## License
- MIT

------

#### more ptojects:
GitHub: https://github.com/tabeaerkelenz
