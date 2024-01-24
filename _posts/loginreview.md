<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <script>
        function login() {
            // Prompt for a code
            var enteredCode = prompt("Enter the access code:");

            // Check if the entered code is correct
            if (enteredCode === "1234") {
                alert("Login successful! Welcome to the website.");
                // Redirect to the main content or perform other actions
            } else {
                alert("Incorrect code. Access denied.");
                // You may choose to handle incorrect attempts differently
            }
        }
    </script>
</head>
<body onload="login()">
    <!-- Other content of your website goes here -->
    <h1>Welcome to My Website</h1>
    <!-- More content... -->
</body>
</html>

