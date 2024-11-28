# Experiment 1: Designing-a-Responsive-layout-for-a-societal-application

## Aim: 
To design a responsive layout for a societal application.

## Algorithm:
1.	HTML and CSS Setup:
●	Create an HTML5 document with character encoding and viewport settings.
●	Use internal CSS to style the layout components.
2.	Reset Default Styles:
●	Reset margins, padding, and specify a font-family for better control.
3.	Style Header, Navigation, Content, and Footer:
●	Apply background colors, text colors, and alignment to the header, navigation, and footer.
●	Style navigation links as inline elements with spacing.
●	Center-align text in header, navigation, and footer.
4.	Implement Responsive Design:
●	Use a media query for screens up to 768px wide.
●	Adjust navigation for mobile display (block-level elements with margin).
5.	Add Content:
●	Place your application's content within the .container div.


## Program:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta	name="viewport"	content="width=device-width, initial-scale=1.0">
<title>Societal Application</title>
<style>
/* Reset some default styles */ body, html {
margin: 0;
padding: 0;
font-family: Arial, sans-serif;
}

/* Header styles */ header {
background-color: #ff0000; color: #fff;
padding: 10px; text-align: center;
}

/* Navigation styles */ nav {
background-color: #47fff0; color: #fff;
text-align: center;
}

nav ul {
list-style: none; padding: 0;
}

nav li {
display: inline; margin: 0 15px;
}

/* Main content styles */
.container {
max-width: 1200px; margin: 0 auto; padding: 20px;
}

/* Responsive design */ @Media (max-width: 768px) {
nav {
display: block; text-align: center;
}

nav li {
display: block; margin: 10px 0;
}
}

/* Footer styles */ footer {
background-color: #0e00d1; color: #fff;
text-align: center; padding: 10px;
}
</style>
</head>
<body>
<header>
<h1>Societal Application</h1>
</header>
<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Profile</a></li>
<li><a href="#">Posts</a></li>
<li><a href="#">Friends</a></li>
<li><a href="#">Settings</a></li>
</ul>
</nav>
<div class="container">
<!-- Your content goes here -->
<h2>Welcome to our Societal Application! </h2>
<p>Lorem ipsum dolor sit amet, consectetur adipescent elite	</p>
</div>
<footer>
&copy; 2023 Societal Application
</footer>
</body>
</html>
```

## OUTPUT:

### DESKTOP VIEW:
![image](https://github.com/user-attachments/assets/c4ca52b5-2693-4dab-934a-823b7b985e45)

### TABLET VIEW:
![image](https://github.com/user-attachments/assets/34bf3b7f-71f8-4f34-a6ca-96854fade4c7)

### PHONE VIEW:
![image](https://github.com/user-attachments/assets/59a554eb-e818-4001-8304-b3e6598d5210)

## Result:
Thus, designing of responsive layout for a societal application has been performed successfully.
