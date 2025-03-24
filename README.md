# Advanced HTML5 Elements and Forms

!DOCTYPE html>
<html>
    <head>
        <title>SUPERSPORT CHANNEL</title>
    </head>
    <body>
        <h2>Ordered List with Roman Numerals</h2>
        <o1 type="I">
            <li>I</li>
            <li>II</li>
            <li>III</li>
            <li>IV</li>
            <li>V</li>
        </o1>
        <hl>Soccer ball</hl>
        <img src="C:\Users\caiphus Laka\Downloads\soccer ball.jpg">
        <h1>Soccer video</h1>
        <video width="640" height="360"controls>"C:\Users\caiphus Laka\Downloads\soocer video.mp4">
        <source src="video.ogg"type="video.mp4">
        </video>
        <h2>Contacts lists</h2>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </thead>
                </tr>
                <tr>
                    <td>David Jones</td>
                    <td>345 Smith Street</td>
                    <td>0784991129</td>
                    <td>davidjones@gmail.com</td>
                </tr>
                <tr>
                    <td>Silvia Brown</td>
                    <td>Mandela street</td>
                    <td>07833915590</td>
                    <td>silviab@gmail.com</td>
                </tr>
                <tr>
                    <td>John Ronald</td>
                    <td>11 Soweto street</td>
                    <td>0873391011</td>
                    <td>johnronald@gmail.com</td>
                </tr>
                <tr>
                    <td>Jane Booth</td>
                    <td>Maiba street</td>
                    <td>0872299146</td>
                    <td>janeb@gmail.com</td>
                </tr>
                <tr>
                    <td>Suzan Stevens</td>
                    <td>naled Street</td>
                    <td>0733199441</td>
                    <td>stevenssuzan@gmail.com</td>
                </tr>
        </table>
        <h2>Registration Form</h2>
        <form action="#" method="post" id="registration-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <label for="password">Password:</label>
            <input type="password"id="password" name="password"placeholder="Enter your password"required minglength="8">
            <label for DOB>Date of birth:</label>
            <input type="date" id="dob"name="dob" required>
            <label for="gender">Gender</label>
            <input type="radio" id="male"name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="Female"name="gender" value="female" required>
            <label for="Female">Female</label>
            <label for="country">Country:</label>
            <select id="country"name="country" required>
                <option value="">Select a country</option>
                <option value="rsa">RSA</option>
                <option value="Kenya">KENYA</option>
            </select>
            <label for="terms">
                <input type="checkbox"id="terms" name="terms" required>
                I agree to the terms and conditions.
            </label>
            <button type="submit">Register</button>
            </form>
        </body>
</html>
