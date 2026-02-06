

#  Notes App (React)

A simple and clean **Notes Taking Application** built with **React** and **Tailwind CSS**.
Users can add, view, and delete notes, with data **persisted using localStorage**, so notes remain even after refreshing the page.

 **Live Demo:** [https://notes-react-pi.vercel.app/](https://notes-react-pi.vercel.app/)</br>
 **GitHub Repo:** [https://github.com/Nabin-09/notes-react](https://github.com/Nabin-09/notes-react)

---

##  Features

*  Add notes with **title and details**
*  Prevents creation of empty notes
*  Delete individual notes
*  Notes stored in **localStorage**
*  Auto-adjusting note size based on content
*  Responsive UI using Tailwind CSS
*  Fast and lightweight React app

---

##  Tech Stack

* **React** (Functional Components & Hooks)
* **Tailwind CSS**
* **localStorage API**
* **Vercel** (Deployment)

---

##  Preview

 Check the live app here:
 [https://notes-react-pi.vercel.app/](https://notes-react-pi.vercel.app/)

---

##  Project Structure

```
notes-react/
│
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── public/
├── package.json
└── README.md
```

---

##  Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/Nabin-09/notes-react.git
```

2. **Navigate to project directory**

```bash
cd notes-react
```

3. **Install dependencies**

```bash
npm install
```

4. **Run the app**

```bash
npm run dev
```

App will start at:
 `http://localhost:5173`

---

##  How It Works

* Notes are stored in React state
* On app load, notes are fetched from `localStorage`
* Every add/delete action updates `localStorage` automatically using `useEffect`
* UI dynamically adjusts note size based on content

---

##  Future Improvements

*  Edit notes
*  Search & filter notes
*  Add tags/categories
*  Dark / Light mode
*  Backend integration (MongoDB / Firebase)

---

##  Author

**Nabin Sharma**

* GitHub: [https://github.com/Nabin-09](https://github.com/Nabin-09)
* Live Projects: [https://notes-react-pi.vercel.app/](https://notes-react-pi.vercel.app/)


