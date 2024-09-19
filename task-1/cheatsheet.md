### Beginner HTML & CSS Challenge: Create a Simple Personal Profile Page

#### Objective:
The goal of this challenge is to create a basic personal profile page using HTML and CSS. This challenge will help you understand how to structure an HTML document and apply simple CSS styles.

---

### Steps

1. **Set up the project**:
   - Create a folder on your computer called `profile-page`.
   - Inside the folder, create two files: `index.html` and `style.css`.

2. **Create the basic HTML structure**:
   - Open `index.html` and start by writing the basic HTML structure:
     ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Personal Profile</title>
         <link rel="stylesheet" href="style.css">
     </head>
     <body>
         <!-- Content will go here -->
     </body>
     </html>
     ```

3. **Add a profile picture**:
   - Inside the `body` tag, add an image element for your profile picture. For now, you can use a placeholder image URL (or download an image of yourself and place it in your folder).
     ```html
     <body>
         <img src="https://via.placeholder.com/150" alt="Profile Picture">
     </body>
     ```

4. **Add your name and a short description**:
   - Below the image, add your name and a short paragraph about yourself.
     ```html
     <body>
         <img src="https://via.placeholder.com/150" alt="Profile Picture">
         <h1>Your Name</h1>
         <p>Hello! I’m a beginner web developer learning HTML and CSS.</p>
     </body>
     ```

5. **Add a contact section**:
   - Below your description, create a contact section with your email and social media links.
     ```html
     <body>
         <img src="https://via.placeholder.com/150" alt="Profile Picture">
         <h1>Your Name</h1>
         <p>Hello! I’m a beginner web developer learning HTML and CSS.</p>
         
         <h2>Contact Me</h2>
         <ul>
             <li>Email: your-email@example.com</li>
             <li>GitHub: <a href="#">github.com/yourusername</a></li>
             <li>LinkedIn: <a href="#">linkedin.com/in/yourusername</a></li>
         </ul>
     </body>
     ```

6. **Style the profile page using CSS**:
   - Now open `style.css` and start adding basic styling:
     
     Here are step-by-step instructions for how to style the HTML content within the `<body>` tag using CSS.


### Steps to Style the `<body>` Content:

1. **Center-align the text**:
   - Add styles to the `body` to center-align the content and apply a basic font.
   - Go to your `style.css` file and add this:
     ```css
     body {
         font-family: Arial, sans-serif;
         background-color: #f0f0f0;
         text-align: center;
         margin: 0;
         padding: 0;
     }
     ```
   - This will center-align all text and set a consistent font.

2. **Style the profile picture (`<img>`)**:
   - Make the profile picture circular and add some margin at the top.
   - In your `style.css` file, add this under the `body` styles:
     ```css
     img {
         border-radius: 50%;
         width: 150px; /* Ensures the image remains a fixed size */
         height: 150px; /* Same as width for a perfect circle */
         margin-top: 20px;
         border: 3px solid #3498db; /* Optional: add a border around the image */
     }
     ```
   - This will make your profile picture circular and add some space above it.

3. **Style your name (`<h1>`)**:
   - Customize the font size and spacing of your name.
   - Add this to your `style.css`:
     ```css
     h1 {
         font-size: 2.5em;
         margin: 10px 0;
         color: #333;
     }
     ```
   - This will increase the font size of your name and add space above and below it.

4. **Style the description (`<p>`)**:
   - Make the paragraph (your short description) a bit more readable by adjusting font size and color.
   - Add this to `style.css`:
     ```css
     p {
         font-size: 1.2em;
         color: #666;
         margin-bottom: 20px;
         line-height: 1.5; /* Adds better spacing between lines */
     }
     ```
   - This will improve the text appearance and spacing in your description.

5. **Style the contact section heading (`<h2>`)**:
   - Increase the font size of the "Contact Me" section.
   - In your `style.css`, add:
     ```css
     h2 {
         font-size: 2em;
         color: #333;
         margin-top: 30px;
     }
     ```
   - This will make the "Contact Me" heading more prominent and add space above it.

6. **Style the contact list (`<ul>` and `<li>`)**:
   - Remove bullet points from the list and add some spacing between list items.
   - Add this in `style.css`:
     ```css
     ul {
         list-style: none; /* Removes bullets */
         padding: 0;
     }

     ul li {
         margin: 5px 0; /* Adds space between each contact item */
         font-size: 1.1em;
     }
     ```
   - This will ensure the contact list looks cleaner and evenly spaced.

7. **Style the contact links (`<a>`)**:
   - Change the color of your links to blue and add an underline on hover.
   - In `style.css`, add:
     ```css
     a {
         text-decoration: none; /* Removes the default underline */
         color: #3498db; /* Changes link color to blue */
     }

     a:hover {
         text-decoration: underline; /* Adds an underline when hovering over the link */
     }
     ```
   - This makes the links more interactive and visually appealing.

8. **Make the page responsive (optional)**:
   - Add a media query to adjust the image size and text for smaller screens (like mobile).
   - In your `style.css`, add:
     ```css
     @media (max-width: 600px) {
         img {
             width: 100px;
             height: 100px;
         }

         h1 {
             font-size: 2em;
         }

         p {
             font-size: 1em;
         }

         h2 {
             font-size: 1.5em;
         }
     }
     ```
   - This will ensure the profile page looks good on smaller screens like mobile phones.

---

### Challenge Completed!

You have now created a basic personal profile page with HTML and CSS. You can experiment by changing the colors, fonts, and layout to make it more personalized.

---

### Starter Code Template:

#### `index.html`:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Profile</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <img src="https://via.placeholder.com/150" alt="Profile Picture">
    <h1>Your Name</h1>
    <p>Hello! I’m a beginner web developer learning HTML and CSS.</p>
    
    <h2>Contact Me</h2>
    <ul>
        <li>Email: your-email@example.com</li>
        <li>GitHub: <a href="#">github.com/yourusername</a></li>
        <li>LinkedIn: <a href="#">linkedin.com/in/yourusername</a></li>
    </ul>
</body>
</html>
```

#### `style.css`:
```css
/* style.css */

/* Basic body styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    text-align: center;
    margin: 0;
    padding: 0;
}

/* Profile image styling */
img {
    border-radius: 50%;
    margin-top: 20px;
}

/* Heading and paragraph styling */
h1 {
    font-size: 2.5em;
    margin: 10px 0;
}

p {
    font-size: 1.2em;
    color: #666;
}

/* Contact section styling */
h2 {
    margin-top: 30px;
    font-size: 2em;
    color: #333;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    margin: 5px 0;
}

a {
    text-decoration: none;
    color: #3498db;
}

a:hover {
    text-decoration: underline;
}
```

Good luck my love! Feel free to explore further by customizing this page with more styles and elements!