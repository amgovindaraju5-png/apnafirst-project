# apnafirst-project
This is my first git repository.
<br>
Author name-Sandhya Shree G
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant/CV page</title>
</head>
<body>
    <header style="background-color:pink;  padding:20px; text-align: center;">
        <h1>My Restaurant</h1>
        <nav>
            <ol type="1" style="list-style-type: none; display: flex; justify-content: center; gap: 20px;">
                <li><a href="#menu">Menu</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#Location">Location</a></li>
                <li><a href="#Reserve">Reserve</a></li>
                <li><a href="#Ambiance">Ambiance</a></li>
            </ol>
        </nav>
    </header>
    <main>
        <section id="menu">
            <h2 style="text-align: center; color: red;"><u>Menu</u></h2>
            <p style="text-align: center;"><big>Explore our delicious offerings, from appetizers to desserts.</big></p>
            <table border="4" style="width: 80%; margin: 0 auto; border-collapse: collapse; text-align: center;">
                <tr>
                    <th style="background-color: lightgoldenrodyellow;">Dish</th>
                    <th style="background-color: lightgoldenrodyellow;">Description</th>
                    <th style="background-color: lightgoldenrodyellow; color: red;"><u>Price</u></th>
                </tr>
                <tr>
                    <td>Grilled Chicken</td>
                    <td>Juicy grilled chicken served with seasonal vegetables.</td>
                    <td style="color: red;">$14.99</td> 
                </tr>       
                <tr>
                    <td>Spaghetti Carbonara</td>
                    <td>Classic Italian pasta with creamy sauce and pancetta.</td>
                    <td style="color: red;">$12.99</td>
                </tr>
                <tr>
                    <td>Margherita Pizza</td>
                    <td>Fresh tomatoes, mozzarella, and basil on a thin crust.</td>
                    <td style="color: red;">$10.99</td>
                </tr>
                <tr>
                    <td>Caesar Salad</td>
                    <td>Crisp romaine lettuce with Caesar dressing and croutons.</td>
                    <td style="color: red;">$8.99</td>
                </tr>
                <tr>
                    <td>Chocolate Lava Cake</td>
                    <td>Warm chocolate cake with a gooey center, served with ice cream.</td>
                    <td style="color: red;">$6.99</td>
                </tr>
            </table>
        </section>
        <section id="gallery">
            <h2 style="text-align: center; color: red;"><u>Gallery</u></h2>
            <p style="text-align: center;"><big>Take a look at our restaurant's ambiance and dishes.</big></p>
            <figure style="text-align: center;">
                <img src="food.jfif" alt="Restaurant Food" width="600">
                <figcaption>Delicious dishes served at our restaurant.</figcaption>
            </figure>
        </section>
        
            <section id="Ambiance">
                <h2 style="text-align: center; color: red;"><u>Ambiance</u></h2>
                <p style="text-align: center;"><big>Experience the cozy and inviting atmosphere of our restaurant.</big></p>
<figure style="text-align: center;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/Zr7MrI9-XwA?si=Jj7ii6IUNGYDrRrR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    <figcaption>Watch our restaurant's ambiance in action!</figcaption>
</figure>
        </section>
        <section id="Location">
            <h2 style="text-align: center; color: red;"><u>Location</u></h2>
            <p style="text-align: center;"><big>Find us at 123 Food Street, Culinary City.</big></p>
            <figure style="text-align: center;">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15529.476142898504!2d75.75360318715823!3d13.327305199999998!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bbad94da9923813%3A0x171c9e7f728673a8!2sKAILASH%20PARBAT%20-%20Chikkamagaluru%20-%20a%20pure%20vegetarian%20restaurant!5e0!3m2!1sen!2sin!4v1786185336455!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
                <figcaption>Our Location on Google Maps</figcaption>
            </figure>
            </section>
        <section id="Reserve">
            <fieldset style="border: 2px solid red; padding: 20px; width: 50%; margin: 0 auto;">
                <legend style="color: red;">Reservation Form</legend>
            <h2 style="text-align: center; color: red;"><u>Reserve</u></h2>
            <p style="text-align: center;"><big>Book your table online for a delightful dining experience.</big></p>
            <form action="reservation.php" method="post">
                <label for="name" style="color: purple;">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email" style="color: purple;">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                <label for="phone" style="color: purple;">Phone Number:</label>
                <input type="number" id="phone" name="phone" placeholder="Phone Number" required><br><br>
                <label for="date" style="color: purple;">Date:</label>
                <input type="date" id="date" name="date" required><br><br>
                <label for="time" style="color: purple;">Time:</label>
                <input type="time" id="time" name="time" required><br><br>
                <label for="guests" style="color: purple;">Number of Guests:</label>
                <input type="number" id="guests" name="guests" min="1" required><br><br>
                <label for="special-requests" style="color: purple;">Special Requests:</label>
                <textarea id="special-requests" name="special-requests" rows="4" cols="50" placeholder="Any special requests?"></textarea><br><br>
            <label for="occasion" style="color: purple;">Occasion:</label>
                <select id="occasion" name="occasion">
                    <option value="birthday">Birthday</option>
                    <option value="anniversary">Anniversary</option>
                    <option value="business">Business Meeting</option>
                    <option value="casual">Casual Dining</option>   
                </select><br><br>
                <label for="seating" style="color: purple;">Seating Preference:</label>
                <input type="radio" id="indoor" name="seating" value="indoor" required>         
                <label for="indoor" style="color: purple;">Indoor</label>
                <input type="radio" id="outdoor" name="seating" value="outdoor" required>
                <label for="outdoor" style="color: purple;">Outdoor</label><br><br>
                <label for="newsletter" style="color: purple;">Subscribe to Newsletter:</label>           
                <input type="checkbox" id="newsletter" name="newsletter" value="yes">
                <label for="newsletter" style="color: purple;">Yes, I want to receive updates and promotions.</label><br><br>     
            
                <input type="reset" value="Reset">  
                <input type="submit" value="Reserve Now">
            </form>
               
        </section>
    </body>
</html>
