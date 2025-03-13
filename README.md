# Advanced HTML5 Elements and Forms

This repository demonstrates advanced HTML5 elements including lists, tables, forms, and multimedia integration.

## Table of Contents
- [Overview](#overview)
- [Features Demonstrated](#features-demonstrated)
- [Code Example](#code-example)
- [Form Validation](#form-validation)
- [Multimedia Elements](#multimedia-elements)
- [Learning Objectives](#learning-objectives)

## Overview

This project showcases advanced HTML5 elements and demonstrates best practices for implementing forms with validation attributes, multimedia elements, and semantic markup.

## Features Demonstrated

- **Ordered List with Roman Numerals:** Uses the `type="I"` attribute to display list items with Roman numerals
- **External Image:** Integrates an image from Pexels with proper `alt` text and `figure`/`figcaption` elements
- **HTML Table:** Creates a structured table of contacts with proper headers and data cells
- **Registration Form:** Implements a comprehensive form with various input types and validation
- **Multimedia:** Includes both audio and video elements with appropriate controls

## Code Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements and Forms</title>
</head>
<body>
    <!-- Header section -->
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
        <p>Demonstrating advanced HTML5 features including lists, tables, forms, and multimedia</p>
    </header>

    <!-- Main content section -->
    <main>
        <!-- Ordered List with Roman Numerals -->
        <section id="ordered-list">
            <h2>Web Development Learning Path</h2>
            <ol type="I">
                <li>HTML Fundamentals</li>
                <li>CSS Styling</li>
                <li>JavaScript Basics</li>
                <li>Responsive Design</li>
                <li>Backend Development</li>
            </ol>
        </section>

        <!-- External Image -->
        <section id="image-section">
            <h2>Featured Image</h2>
            <figure>
                <img src="https://images.pexels.com/photos/270348/pexels-photo-270348.jpeg" 
                     alt="Computer code on a screen" 
                     width="600" 
                     height="400">
                <figcaption>Web development code (Source: Pexels)</figcaption>
            </figure>
        </section>

        <!-- Table of Contacts -->
        <section id="contacts-table">
            <h2>Contact Directory</h2>
            <table border="1">
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Address</th>
                        <th>Mobile</th>
                        <th>Email</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Kimoloi Meshack</td>
                        <td>Uasin Gishu, Eldoret</td>
                        <td>+254712345678</td>
                        <td>ChirchirMeshack@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Jane Ndung'u</td>
                        <td>Kiambu,Juja</td>
                        <td>+254712345678</td>
                        <td>janendung'u@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Robert Johnson</td>
                        <td>789 Pine Rd, Elsewhere</td>
                        <td>(555) 234-5678</td>
                        <td>robert.j@example.com</td>
                    </tr>
                    <tr>
                        <td>Emily Davis</td>
                        <td>321 Cedar Ln, Nowhere</td>
                        <td>(555) 876-5432</td>
                        <td>emily.d@example.com</td>
                    </tr>
                    <tr>
                        <td>Michael Wilson</td>
                        <td>654 Birch Blvd, Anywhere</td>
                        <td>(555) 345-6789</td>
                        <td>michael.w@example.com</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Registration Form -->
        <section id="registration">
            <h2>Registration Form</h2>
            <form action="#" method="post">
                <!-- Form elements here -->
            </form>
        </section>

        <!-- Multimedia Elements -->
        <section id="multimedia">
            <h2>Multimedia Examples</h2>
            
            <!-- Audio Element -->
            <h3>Audio Sample</h3>
            <audio controls>
                <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            
            <!-- Video Element -->
            <h3>Video Sample</h3>
            <video width="320" height="240" controls>
                <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </section>
    </main>

    <!-- Footer section -->
    <footer>
        <p>&copy; 2025 Advanced HTML5 Tutorial. All rights reserved.</p>
    </footer>
</body>
</html>
```

## Form Validation

The registration form implements several HTML5 validation features:

| Input Type | Validation Applied |
|------------|-------------------|
| Text (Name) | Required attribute ensures the field cannot be empty |
| Email | Email type validation ensures a valid email format |
| Password | Pattern attribute enforces strong password requirements (uppercase, lowercase, number, 8+ chars) |
| Date | Required attribute ensures a date must be selected |
| Select (Country) | Required attribute ensures a country must be selected |
| Radio (Gender) | Required attribute ensures one option must be selected |

### Validation Attributes Used:

- `required`: Makes the field mandatory
- `minlength`: Sets minimum character length
- `pattern`: Defines a regex pattern for validation
- `type="email"`: Validates email format
- `type="date"`: Ensures proper date selection
- `placeholder`: Provides input hints

## Multimedia Elements

The document demonstrates two key multimedia elements:

1. **Audio Element**: 
   - Implements the `<audio>` tag with controls
   - Includes a fallback message for browsers that don't support the element
   - Uses the `<source>` tag to specify the audio file format

2. **Video Element**:
   - Implements the `<video>` tag with controls
   - Specifies width and height attributes
   - Includes a fallback message for browsers that don't support the element
   - Uses the `<source>` tag to specify the video file format

## Learning Objectives

This project addresses the following learning objectives:

- ✅ Implementing HTML5 images, lists, tables, forms, and input types
- ✅ Using form validation attributes
- ✅ Applying multimedia elements such as audio and video
- ✅ Creating semantic HTML structure
- ✅ Proper use of labels and accessibility attributes

## Getting Started

1. Clone this repository or download the files
2. Open `index.html` in your browser to see the rendered page
3. Examine the HTML code to understand the implementation of each feature
4. Experiment by modifying the code to see how changes affect the page

## Best Practices Demonstrated

- Semantic HTML5 structure
- Proper form labeling and accessibility
- Client-side form validation
- Responsive design considerations
- Fallback content for unsupported elements

Happy Coding! 💻✨
