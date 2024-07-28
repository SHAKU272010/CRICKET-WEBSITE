
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desi Cricket Diaries</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Desi Cricket Diaries</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#team">Team</a></li>
            <li><a href="#schedule">Schedule</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Welcome to Desi Cricket Diaries</h2>
            <p>Your ultimate source for all cricket updates and club details.</p>
        </section>
        <section id="team">
            <h2>Our Team</h2>
            <div class="team-container">
                <!-- Team members details -->
                <div class="team-member">
                    <img src="team_member_1.jpg" alt="Team Member 1">
                    <h3>Team Member 1</h3>
                    <p>Position: Batsman</p>
                </div>
                <div class="team-member">
                    <img src="team_member_2.jpg" alt="Team Member 2">
                    <h3>Team Member 2</h3>
                    <p>Position: Bowler</p>
                </div>
                <!-- Add more team members as needed -->
            </div>
        </section>
        <section id="schedule">
            <h2>Match Schedule</h2>
            <table>
                <tr>
                    <th>Date</th>
                    <th>Opponent</th>
                    <th>Venue</th>
                </tr>
                <tr>
                    <td>2024-08-01</td>
                    <td>Team A</td>
                    <td>Stadium 1</td>
                </tr>
                <tr>
                    <td>2024-08-05</td>
                    <td>Team B</td>
                    <td>Stadium 2</td>
                </tr>
                <!-- Add more matches as needed -->
            </table>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <label for="message">Message:</label>
                <textarea id="message" name="message"></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Desi Cricket Diaries. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
