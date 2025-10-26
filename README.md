# educational-website-html
# Track and Field Website

This project is a simple two-page educational website about Track and Field.  
It was built using semantic HTML tags to structure and organize the content.  

## Features
- Multiple header tags and paragraph tags
- Unordered and ordered lists
- Internal links between pages
- Image with relative path, alt text, and width
- Semantic tags: `<header>`, `<main>`, `<section>`, `<footer>`

## File Structure
git add .
git commit -m "Created index.html with track and field overview"
git add .
git commit -m "Added page2.html with training tips and structure"
git add .
git commit -m "Inserted image and added internal links between pages"
git push
/* style.css */
body {
  font-family: Arial, sans-serif;
  background-color: #fafafa;
  margin: 0;
  padding: 0;
}

header {
  background-color: #e63946;
  color: white;
  text-align: center;
  padding: 20px;
}

h1, h2, h3 {
  font-weight: bold;
}

img {
  display: block;
  margin: 20px auto;
  border-radius: 8px;
}

footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 10px;
}

a {
  color: #f1faee;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
