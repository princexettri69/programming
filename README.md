<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurant Reservation</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Make a Reservation</h1>
    <form action="#" method="post">
      
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone:</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="date">Date:</label>
      <input type="date" id="date" name="date" required>

      <label for="time">Time:</label>
      <input type="time" id="time" name="time" required>

      <label for="guests">Number of Guests:</label>
      <input type="number" id="guests" name="guests" min="1" required>

      <label for="specialRequest">Special Requests:</label>
      <textarea id="specialRequest" name="specialRequest" rows="4"></textarea>
     </class>
      <input type="submit" value="Submit">
    </form>
  </div>
</body>
</html>

