<!DOCTYPE html>
<html lang="en">
<head>
	//there we go the code . with all the furture and there we go	//we no aall 
// pushing code to the test branch
//  change 
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comprehensive Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        h1, h2 {
            color: #333;
        }
        .card {
            background-color: white;
            border: 1px solid #ddd;
            padding: 15px;
            margin: 10px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .form-container {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        input[type="text"], input[type="email"], input[type="submit"] {
            padding: 10px;
            margin: 10px 0;
            width: 100%;
            border: 1px solid #ccc;
        }
        .table-container {
            margin-top: 20px;
            overflow-x: auto;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <header>
        <h1>My Comprehensive Webpage</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="home">
            <div class="card">
                <h2>Welcome to the Homepage</h2>
                <p>This is a more detailed webpage with various elements like a navigation bar, form, table, and an image.</p>
                <img src="https://via.placeholder.com/600x300" alt="Sample Image" style="width:100%; max-width:600px;">
            </div>
        </section>

        <section id="about">
            <div class="card">
                <h2>About Us</h2>
                <p>We are a company dedicated to providing great web design and development services. Our team works hard to create amazing user experiences.</p>
            </div>
        </section>

        <section id="contact">
            <div class="form-container">
                <h2>Contact Us</h2>
                <form action="#" method="post">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                    
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                    
                    <input type="submit" value="Submit">
                </form>
            </div>
        </section>

        <section>
            <div class="table-container">
                <h2>Our Services</h2>
                <table>
                    <tr>
                        <th>Service</th>
                        <th>Description</th>
                        <th>Price</th>
                    </tr>
                    <tr>
                        <td>Web Design</td>
                        <td>Creating stunning websites with a focus on user experience.</td>
                        <td>$500</td>
                    </tr>
                    <tr>
                        <td>SEO Optimization</td>
                        <td>Improving your site's visibility on search engines.</td>
                        <td>$300</td>
                    </tr>
                    <tr>
                        <td>Consulting</td>
                        <td>Providing expert advice on web development strategies.</td>
                        <td>$150</td>
                    </tr>
                </table>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 My Company. All Rights Reserved.</p>
    </footer>

</body>
</html>
