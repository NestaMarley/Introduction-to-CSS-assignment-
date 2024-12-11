# Introduction-to-CSS-assignment-
Part 1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Basics</title>
    <link rel="stylesheet" href="styles.css"> <!-- External CSS link -->
    <style>
        /* Internal CSS */
        h1, h2, h3 {
            font-size: 24px; /* Element Selector */
        }
        .highlight {
            background-color: lightyellow; /* Class Selector */
        }
        #uniqueElement {
            border: 2px solid blue; /* ID Selector */
        }
    </style>
</head>
<body>

    <h1>Welcome to My Website</h1>
    <div class="highlight">
        <h2>About Us</h2>
        <p>This website is all about learning CSS.</p>
    </div>
    <div id="uniqueElement">
        <h2>Contact</h2>
        <p>Email us at contact@example.com</p>
    </div>

    <p style="color: red;">This is an inline styled paragraph.</p> <!-- Inline CSS -->

</body>
</html>

Part 2.
/* External CSS */
body {
    background-color: #f0f8ff; /* Light background color */
}

a {
    color: blue;
    text-decoration: none;
}

a:hover {
    color: darkorange; /* Hover effect */
    text-decoration: underline;
}

* {
    box-sizing: border-box;
}

@media (max-width: 600px) {
    h1 {
        font-size: 20px;
    }
    h2 {
        font-size: 18px;
    }
    p {
        font-size: 16px;
    }
}

Part 3

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Basics</title>
    <link rel="stylesheet" href="styles.css"> .card {
    background-color: #ffffff; /* Light background color */
    border: 1px solid #ccc; /* Subtle border */
    padding: 20px; /* Padding inside the card */
    margin: 15px; /* Margin around the card */
    border-radius: 5px; /* Rounded corners */
    width: 300px; /* Fixed width for the card */
    text-align: center; /* Center-align text */
}

/* Responsive card styling */
@media (max-width: 600px) {
    .card {
        width: 90%; /* Full width on smaller screens */
    }
}
    <style>
        /* Internal CSS */
        h1, h2, h3 {
            font-size: 24px; /* Element Selector */
        }
        .highlight {
            background-color: lightyellow; /* Class Selector */
        }
        #uniqueElement {
            border: 2px solid blue; /* ID Selector */
        }
    </style>
</head>
<body>

    <div class="card">
    <h3>Card Title</h3>
    <p>This is a description of the card content.</p>
</div>

</body>
</html>

