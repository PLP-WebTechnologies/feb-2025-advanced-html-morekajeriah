# Advanced HTML5 Elements and Forms
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Orbitron', sans-serif;
            background-color: #121212;
            color: #0ff;
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            color: #0ff;
        }
        th, td {
            border: 1px solid #0ff;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #222;
        }
        input, select, button {
            background-color: #222;
            color: #0ff;
            border: 1px solid #0ff;
            padding: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>
    
    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List</h2>
        <ol type="I">
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Python</li>
            <li>SQL</li>
        </ol>
    </section>
    
    <!-- External Image -->
    <section>
        <h2>External Image</h2>
        <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Beautiful Scenery" width="600">
    </section>
    
    <!-- Table with Contacts -->
    <section>
        <h2>Contact List</h2>
        <table>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>123 Elm Street</td>
                <td>+1234567890</td>
                <td>johndoe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Avenue</td>
                <td>+9876543210</td>
                <td>janesmith@example.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>789 Pine Road</td>
                <td>+1122334455</td>
                <td>michaelbrown@example.com</td>
            </tr>
            <tr>
                <td>Emily Johnson</td>
                <td>321 Cedar Lane</td>
                <td>+5566778899</td>
                <td>emilyjohnson@example.com</td>
            </tr>
            <tr>
                <td>Robert Wilson</td>
                <td>654 Maple Drive</td>
                <td>+6677889900</td>
                <td>robertwilson@example.com</td>
            </tr>
        </table>
    </section>
    
    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a password" required>
            <br><br>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>
            
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male"> <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female"> <label for="female">Female</label>
            <br><br>
            
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
                <option value="australia">Australia</option>
            </select>
            <br><br>
            
            <label>Interests:</label>
            <input type="checkbox" id="sports" name="interests" value="sports"> <label for="sports">Sports</label>
            <input type="checkbox" id="music" name="interests" value="music"> <label for="music">Music</label>
            <input type="checkbox" id="reading" name="interests" value="reading"> <label for="reading">Reading</label>
            <br><br>
            
            <button type="submit">Register</button>
        </form>
    </section>
</body>
</html>
