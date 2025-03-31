# Html-Assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML5 Elements Demo</title>
</head>
<body>
   
    <header>
        <h1>HTML5 Elements Demonstration</h1>
    </header>

 
    <section>
        <h2>Ordered List (Roman Numerals)</h2>
        <ol type="I">
            <li>Iphone 13pro</li>
            <li>HP 250 Notebook pc</li>
            <li>Makito headsets</li>
            <li>Makito charger</li>
            <li>Makito bag</li>
        </ol>
    </section>

    <section>
        <h2>External Image</h2>
        <img src="https://www.shopify.com/stock-photos/photos/camera-phone-laptop-a-photographers-desk?c=photographer/" alt="Flowers" width="500">
    </section>

   
    <section>
        <h2>Contact List</h2>
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
                    <td>Jabu Langa</td>
                    <td>1234 patrick St, Springfield</td>
                    <td>(+27) 456-7890</td>
                    <td>jabs@gmail.com</td>
                </tr>
                <tr>
                    <td>PHIL Smith</td>
                    <td>5678 Qwabe St, Sharpville</td>
                    <td>(+27) 654-3210</td>
                    <td>PHILsmith@gmail.com</td>
                </tr>
                <tr>
                    <td>ZAKES MASANGO</td>
                    <td>100 MKI, RICHMOND</td>
                    <td>(+27) 555-1234</td>
                    <td>ZAKES@gmail.com</td>
                </tr>
                <tr>
                    <td>MIKE </td>
                    <td>123 JACKS Rd, DURBAN</td>
                    <td>(+27) 555-2345</td>
                    <td>MIKEM@gmail.com</td>
                </tr>
                <tr>
                    <td>MUSA JACOBSON</td>
                    <td>1 KIND EDWARD, IXOPO</td>
                    <td>(+33) 555-6789</td>
                    <td>musa.Jg@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a strong password" required><br><br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

        
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="a">Algeria</option>
                <option value="">Select your country</option>
                <option value="us">United States</option>
                <option value="sa">South Africa</option>
                <option value="ca">Canada</option>
                <option value="ca">Cameroon</option>
                <option value="uk">United Kingdom</option>
                <option value="au">Australia</option>
                <option value="zim">Zimbabwe</option>
            </select><br><br>

            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label><br><br>

            <label>Preferences:</label><br>
            <input type="checkbox" id="newsletter" name="newsletter">
            <label for="newsletter">Subscribe to newsletter</label><br><br>

            <input type="submit" value="Register">
        </form>
    </section>

    <section>
        <h2>Multimedia</h2>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio><br><br>

        <video width="320" height="240" controls>
            <source src="https://www.w3schools.com/html/movie.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>

    <footer>
        <p>MY HTML5 elements demonstration</p>
    </footer>

</body>
</html>

