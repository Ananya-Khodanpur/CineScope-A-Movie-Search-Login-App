# 🎬 CineScope – Login & Movie Search App

CineScope is a simple web project that combines **user login validation** with a **movie search feature** powered by the [OMDB API](https://www.omdbapi.com/).  
It allows users to log in with predefined credentials and search for movies with details like title, year, and posters.

---

## 🚀 Features
- 🔑 **User Authentication** – Validates login using a local `users.json` file  
- 🎥 **Movie Search** – Fetches real-time movie data from OMDB API  
- 🖼️ **Fallback Poster** – Displays a default image if a movie poster is unavailable  
- 🎨 **Modern UI/UX** – Responsive design with hover effects, gradients, and clean layouts  
- ⚡ **Lightweight & Fast** – Built only with HTML, CSS, and JavaScript  

---

## 🛠️ Tech Stack
- **HTML5**  
- **CSS3** (modern gradients, transitions, responsive grid layout)  
- **JavaScript (ES6+)** – API calls, DOM manipulation, user validation  
- **OMDB API** – Movie data source  

---

## 📂 Project Structure
├── index.html # Main app file (login + movie search UI)
├── users.json # Local file containing predefined user credentials
├── style.css # (Optional) Extracted CSS if separated from HTML
├── download.jpeg # Default poster image (for movies without posters)

## 🔧 Setup & Usage
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/cinescope.git
   cd cinescope

2. Make sure the users.json file exists in the same directory as index.html. Example:

3. Open index.html in a browser.

4. Login with one of the users from users.json.

5. Search for any movie title and enjoy browsing results.

🔑 Default Login Credentials

Example users:

Email: Alice@gmail.com
 | Password: 1234

Email: Bob@gmail.com
 | Password: 5678

Email: Anu@gmail.com
 | Password: 7685

🙌 Acknowledgements

OMDB API
 for providing movie data

Inspiration from building small projects to strengthen frontend skills
