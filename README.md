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
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>HTML5 Practice Page</title>
  <!-- Styles for basic layout -->
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    header, section, footer {
      margin-bottom: 20px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    table, th, td {
      border: 1px solid #ccc;
    }
    th, td {
      padding: 8px;
      text-align: left;
    }
    form div {
      margin-bottom: 10px;
    }
    label {
      display: inline-block;
      width: 100px;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>HTML5 Elements Practice</h1>
  </header>

  <!-- Section: Ordered List -->
  <section>
    <h2>Ordered List with Roman Numerals</h2>
    <!-- Ordered list using roman numerals -->
    <ol type="I">
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
    </ol>
  </section>

  <!-- Section: External Image -->
  <section>
    <h2>External Image from Pexels</h2>
    <!-- Using an external image from Pexels -->
    <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" 
         alt="Beautiful Landscape" 
         width="600">
  </section>

  <!-- Section: Contacts Table -->
  <section>
    <h2>Contacts Table</h2>
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
          <td>John Doe</td>
          <td>123 Elm Street</td>
          <td>123-456-7890</td>
          <td>john@example.com</td>
        </tr>
        <tr>
          <td>Jane Smith</td>
          <td>456 Oak Avenue</td>
          <td>234-567-8901</td>
          <td>jane@example.com</td>
        </tr>
        <tr>
          <td>Mike Johnson</td>
          <td>789 Pine Road</td>
          <td>345-678-9012</td>
          <td>mike@example.com</td>
        </tr>
        <tr>
          <td>Emily Davis</td>
          <td>321 Maple Drive</td>
          <td>456-789-0123</td>
          <td>emily@example.com</td>
        </tr>
        <tr>
          <td>David Wilson</td>
          <td>654 Cedar Blvd</td>
          <td>567-890-1234</td>
          <td>david@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Section: Registration Form -->
  <section>
    <h2>Registration Form</h2>
    <form action="#" method="post" novalidate>
      <!-- Name field -->
      <div>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
      </div>
      <!-- Email field -->
      <div>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="example@domain.com" required>
      </div>
      <!-- Password field -->
      <div>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6">
      </div>
      <!-- Date field -->
      <div>
        <label for="dob">Date:</label>
        <input type="date" id="dob" name="dob" required>
      </div>
      <!-- Dropdown menu -->
      <div>
        <label for="country">Country:</label>
        <select id="country" name="country" required>
          <option value="">Select your country</option>
          <option value="usa">USA</option>
          <option value="uk">UK</option>
          <option value="canada">Canada</option>
          <option value="australia">Australia</option>
        </select>
      </div>
      <!-- Radio buttons -->
      <div>
        <span>Gender:</span>
        <label for="male">
          <input type="radio" id="male" name="gender" value="male" required> Male
        </label>
        <label for="female">
          <input type="radio" id="female" name="gender" value="female" required> Female
        </label>
        <label for="other">
          <input type="radio" id="other" name="gender" value="other" required> Other
        </label>
      </div>
      <!-- Checkboxes -->
      <div>
        <span>Interests:</span>
        <label for="sports">
          <input type="checkbox" id="sports" name="interests" value="sports"> Sports
        </label>
        <label for="music">
          <input type="checkbox" id="music" name="interests" value="music"> Music
        </label>
        <label for="movies">
          <input type="checkbox" id="movies" name="interests" value="movies"> Movies
        </label>
      </div>
      <!-- Submit button -->
      <div>
        <button type="submit">Register</button>
      </div>
    </form>
  </section>

  <!-- Section: Multimedia Elements -->
  <section>
    <h2>Multimedia Elements</h2>
    <!-- Audio element -->
    <div>
      <h3>Audio</h3>
      <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    </div>
    <!-- Video element -->
    <div>
      <h3>Video</h3>
      <video width="600" controls>
        <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </section>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2025 HTML5 Practice Page</p>
  </footer>

</body>
</html>

