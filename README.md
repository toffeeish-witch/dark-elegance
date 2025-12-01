# dark-elegance

/* ==========================================
   Wolf Bio Theme: Black | Silver | Gold
   Aesthetic: Regal • Shadowed • Ancient Court
   Author: (Your Name)
========================================== */

@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600&display=swap');

body {
  background-color: #0b0b0b;
  color: #d9d9d9;
  font-family: 'Cormorant Garamond', serif;
  line-height: 1.7;
  margin: 0;
  padding: 0;
  background-image: url('https://i.ibb.co/Y3tWNwn/dark-texture-bg.jpg');
  background-size: cover;
  background-attachment: fixed;
}

/* --- MAIN CARD CONTAINER --- */
.bio-card {
  max-width: 750px;
  background: rgba(15, 15, 15, 0.9);
  margin: 3em auto;
  padding: 2.5em 3em;
  border-radius: 20px;
  border: 1px solid #4a4a4a;
  box-shadow: 0 0 35px rgba(0, 0, 0, 0.8);
}

/* --- HEADERS --- */
h1 {
  text-align: center;
  color: #c7a74f;
  font-size: 2.4em;
  letter-spacing: 1px;
  margin-bottom: 0.2em;
  text-shadow: 0 0 10px rgba(199, 167, 79, 0.6);
}

h2 {
  color: #c7a74f;
  border-bottom: 1px solid #555;
  padding-bottom: 0.3em;
  margin-top: 1.8em;
  letter-spacing: 0.5px;
}

/* --- QUOTES --- */
.quote {
  text-align: center;
  color: #bfbfbf;
  font-style: italic;
  margin-bottom: 1.5em;
}

/* --- IMAGE --- */
.wolf-image {
  display: flex;
  justify-content: center;
  margin: 1.5em 0;
}

.wolf-image img {
  width: 80%;
  max-width: 400px;
  border-radius: 12px;
  border: 1px solid #888;
  box-shadow: 0 0 20px rgba(199, 167, 79, 0.15);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.wolf-image img:hover {
  transform: scale(1.02);
  box-shadow: 0 0 25px rgba(199, 167, 79, 0.25);
}

/* --- DETAILS GRID --- */
.details {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 0.8em 2em;
  margin-bottom: 1.5em;
}

.details p {
  margin: 0;
  color: #ddd;
  font-size: 1.05em;
}

/* --- LISTS --- */
ul {
  margin: 0.5em 0 0.5em 1.3em;
  padding: 0;
}

ul li {
  margin-bottom: 0.4em;
}

/* --- DIVIDERS --- */
.divider {
  text-align: center;
  color: #c7a74f;
  margin: 1.8em 0;
  letter-spacing: 3px;
}

/* --- LINKS --- */
a {
  color: #c7a74f;
  text-decoration: none;
  transition: color 0.2s ease;
}

a:hover {
  color: #e3c86b;
  text-decoration: underline;
}

/* --- FOOTER --- */
.footer {
  text-align: center;
  font-size: 0.9em;
  color: #aaa;
  margin-top: 2.5em;
  border-top: 1px solid #2a2a2a;
  padding-top: 1em;
}

/* --- TEXT HIGHLIGHT --- */
::selection {
  background-color: #c7a74f;
  color: #000;
}

/* --- RESPONSIVE DESIGN --- */
@media (max-width: 600px) {
  .bio-card {
    padding: 1.8em 1.5em;
  }

  h1 {
    font-size: 1.9em;
  }

  .wolf-image img {
    width: 100%;
  }
}
