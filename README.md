# Putting it all Together 
![Animal shelter page with a navbar, cat and dog cards with photos, a contact form, and a footer for easy navigation and interaction](./assets/images/example.png)
##

## Description 📄
In this assignment, you will work solo with the help of AI to build an animal shelter webpage using Bootstrap. You'll create a navbar, animal cards, contact form and a footer. Use AI to assist with coding, design choices, and troubleshooting as you develop a responsive and accessible webpage with Bootstrap's built-in components.

## Expected Project Structure 🏗️

```plaintext

animalShelter/
│
├── index.html
├── styles.css

```
# Instructions ✅

## 1. **Create the Project Folder and Files**
   - [ ] Create a folder named `animalShelter` to store all your project files.
   
   - [ ] Inside the `animalShelter`` folder, create a file named `index.html`. This will be your main HTML file.
   
   - [ ] Also, in the `animalShelter` folder, create another file named `styles.css`. This file will contain the CSS used to style your HTML content.

## 2. **Start with an HTML Boilerplate**
Now that your files are set up, begin by adding the basic HTML boilerplate.


  - [ ] Ask AI to help you prepare an HTML boilerplate. Copy and paste that code into your `index.html` file.

The boilerplate code should look something like this:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
       content="width=device-width, initial-scale=1.0">
  <title>Animal Shelter</title>

  <!-- Bootstrap CDN Goes Here -->

  <link rel="stylesheet"
       href="styles.css">
</head>
<body>
<!-- Web page code goes here -->
</body>
</html>
```

**Explanation:**
- Declares the document as HTML5 and sets up the essential metadata and styles.

## 3. **Access Bootstrap Styling**
Now we will add a CDN link to access Bootstrap for styling our web page.


- [ ] Copy and paste the link below into the `<head>` of your HTML boilerplate, right after the `<title>`

```html

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
rel="stylesheet" 
integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
crossorigin="anonymous">

```

**Explanation:**
- By adding the CDN link, we included Bootstrap's CSS to style our web page with its predefined classes and components.