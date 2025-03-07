<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Healthcare Assistant</title>

    <link rel="icon" type="image/png" href="eww.png">
    <link rel="stylesheet" href="css1.css">
</head>
<body style="background-color: powderblue;">
    <header>
        <h1>Healthcare Assistant</h1>
        <nav>
            <ul>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h2>Your Health, Our Priority</h2>
            <p>Providing compassionate and professional healthcare assistance.</p>
            <a href="#services" class="cta-button">Learn More</a>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <div class="service">
                <h3>Personal Care</h3>
                <p>Assistance with daily living activities.</p>
            </div>
            <div class="service">
                <h3>Medication Management</h3>
                <p>Ensuring proper medication administration.</p>
            </div>
            <div class="service">
                <h3>Companionship</h3>
                <p>Providing companionship and emotional support.</p>
            </div>
        </section>
        
    
        <div class="container">
            <h1>Application Form</h1>
            <form action="#" method="post">
                <fieldset>
                    <legend>Personal Information</legend>
                    <label for="first-name">First Name:</label>
                    <input type="text" id="first-name" name="first-name" required>
    
                    <label for="last-name">Last Name:</label>
                    <input type="text" id="last-name" name="last-name" required>
    
                    <label for="dob">Date of Birth:</label>
                    <input type="date" id="dob" name="dob" required>
    
                    <label for="gender">Gender:</label>
                    <select id="gender" name="gender" required>
                        <option value="">Select...</option>
                        <option value="male">Male</option>
                        <option value="female">Female</option>
                        <option value="other">Other</option>
                    </select>
                </fieldset>
    
                <fieldset>
                    <legend>Contact Information</legend>
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
    
                    <label for="phone">Phone Number:</label>
                    <input type="tel" id="phone" name="phone" required>
    
                    <label for="address">Address:</label>
                    <textarea id="address" name="address" rows="4" required></textarea>
                </fieldset>
    
                <fieldset>
                    <legend>Health Information</legend>
                    <label for="diseases">Select any known diseases or health conditions:</label>
                    <div>
                        <input type="checkbox" id="diabetes" name="diseases" value="Diabetes">
                        <label for="diabetes">Diabetes</label>
                    </div>
                    <div>
                        <input type="checkbox" id="hypertension" name="diseases" value="Hypertension">
                        <label for="hypertension">Hypertension</label>
                    </div>
                    <div>
                        <input type="checkbox" id="asthma" name="diseases" value="Asthma">
                        <label for="asthma">Asthma</label>
                    </div>
                    <div>
                        <input type="checkbox" id="heart-disease" name="diseases" value="Heart Disease">
                        <label for="heart-disease">Heart Disease</label>
                    </div>
                    <div>
                        <input type="checkbox" id="cancer" name="diseases" value="Cancer">
                        <label for="cancer">Cancer</label>
                    </div>
                    <div>
                        <input type="checkbox" id="other" name="diseases" value="Other">
                        <label for="other">Other (please specify):</label>
                        <input type="text" id="other-disease" name="other-disease">
                    </div>
                </fieldset>

    
                <button type="submit">Submit Application</button>
            </form>
    </main>

    <footer>
        <p>&copy; 2023 Healthcare Assistant. All rights reserved.</p>
        <div id="contact">
            <h3>Contact Us</h3>
            <p>Email: info@healthcareassistant.com</p>
            <p>Phone: (123) 456-7890</p>
        </div>
    </footer>
</body>
</html>
