# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements and Forms</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        form {
            max-width: 400px;
            margin: 20px auto;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            box-sizing: border-box;
        }
    </style>
</head>
<body>

    <h1>Advanced HTML5 Elements and Forms</h1>

    <h2>Ordered List</h2>
    <ol type="I">
        <li>moxie-nganya</li>
        <li>hisense screen</li>
        <li>pioneer double-coil speaker</li>
    </ol>

    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/356378/pexels-photo-356378.jpeg" alt="Nature Image" width="300">

    
    <h2>Contacts</h2>
    <table>
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
                <td>John Ndungu</td>
                <td>kangundo road</td>
                <td>0749899767</td>
                <td>john.Ndungu@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Atieno</td>
                <td>Koinange street</td>
                <td>0732456788</td>
                <td>jane.atieno@gmail.com</td>
            </tr>
            <tr>
                <td>Alice Wahome</td>
                <td>pipeline</td>
                <td>0723567456</td>
                <td>alice.wahome@example.com</td>
            </tr>
            <tr>
                <td>Bob Marley</td>
                <td>kingston</td>
                <td>555-4321</td>
                <td>bob.marley@example.com</td>
            </tr>
            <tr>
                <td>Charlie Charplin</td>
                <td>Kayole</td>
                <td>0745678943</td>
                <td>charlie.charplin@example.com</td>
            </tr>
        </tbody>
    </table>

    <h2>Registration Form</h2>
    <form action="/submit" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required placeholder="Enter your name">

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required placeholder="Enter your email">

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required placeholder="Enter your password">

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>

        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="">Select</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>

        <label>Subscription:</label>
        <input type="radio" id="yes" name="subscription" value="yes" required>
        <label for="yes">Yes</label>
        <input type="radio" id="no" name="subscription" value="no">
        <label for="no">No</label>

        <label>Newsletter:</label>
        <input type="checkbox" id="newsletter" name="newsletter">
        <label for="newsletter">Subscribe to newsletter</label>

        <button type="submit">Register</button>
    </form>

</body>
</html>
