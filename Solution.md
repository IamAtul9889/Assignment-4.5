# Assignment 4.5 — Multi-Page College Club Website

Create these files:

```text
college-club/
├── index.html
├── about.html
├── registration.html
├── contact.html
└── style.css
```

### `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="College Club Website">
    <title>College Club</title>
    <link rel="icon" href="images/favicon.ico">
    <link rel="stylesheet" href="style.css">
</head>
<body>
<nav>
<a href="index.html">Home</a>
<a href="about.html">About</a>
<a href="registration.html">Registration</a>
<a href="contact.html">Contact</a>
</nav>

<h1>Welcome to College Club</h1>
<p>We organize coding competitions, workshops, and cultural events.</p>

<table border="1">
<tr><th>Event</th><th>Date</th></tr>
<tr><td>Coding Contest</td><td>10 November</td></tr>
<tr><td>Tech Workshop</td><td>15 November</td></tr>
</table>
</body>
</html>
```

### `about.html`
```html
<h1>About Our Club</h1>
<p>Our club develops students' technical and teamwork skills.</p>
<h2>Members</h2>
<p>Rahul — President</p>
<p>Priya — Secretary</p>
<a href="index.html">Home</a>
```

### `registration.html`
```html
<h1>Student Registration</h1>
<form>
<input type="text" placeholder="Full Name" required>
<input type="email" placeholder="Email" required>
<input type="text" placeholder="Roll Number" required>
<button type="submit">Register</button>
</form>
<a href="index.html">Home</a>
```

### `contact.html`
```html
<h1>Contact Us</h1>
<p>Email: collegeclub@example.com</p>
<p>Phone: 9876543210</p>
<p>Location: College Campus, Uttar Pradesh</p>
<a href="index.html">Home</a>
```

### `style.css`
```css
body {
    font-family: Arial, sans-serif;
    background: #f4f7fb;
    margin: 20px;
}
nav {
    background: navy;
    padding: 15px;
}
nav a {
    color: white;
    margin: 10px;
}
h1 {
    color: navy;
}
input {
    display: block;
    margin: 10px 0;
    padding: 8px;
}
```

**Testing:** Open `index.html` with Live Server and test all page links. Add `images/favicon.ico` for the favicon. The registration form needs a backend to save submitted data.