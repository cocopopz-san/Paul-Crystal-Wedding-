# Paul-Crystal-Wedding-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Chrissy & [Partner's Name] Wedding</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      background-color: #fff8f0;
      color: #333;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background: #f3e5e1;
      padding: 60px 20px;
    }
    header h1 {
      font-size: 48px;
      margin: 0;
    }
    header p {
      font-size: 24px;
      margin-top: 10px;
    }
    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }
    .rsvp-form input, .rsvp-form select, .rsvp-form textarea {
      display: block;
      width: 90%;
      max-width: 500px;
      margin: 10px auto;
      padding: 10px;
      font-size: 16px;
    }
    .rsvp-form button {
      background-color: #d4a5a5;
      color: white;
      padding: 12px 30px;
      font-size: 18px;
      border: none;
      cursor: pointer;
    }
    footer {
      background-color: #f3e5e1;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Chrissy & [Partner's Name]</h1>
    <p>We're Getting Married!</p>
    <p><strong>[Wedding Date]</strong> | [Venue Name, City]</p>
  </header>

  <section>
    <h2>Our Story</h2>
    <p>It all started with a glance, a smile, and one unforgettable date. We've built a life filled with love, laughter, and memories — and we can't wait to celebrate the next chapter with you.</p>
  </section>

  <section>
    <h2>The Wedding</h2>
    <p><strong>Date:</strong> [Insert Date]</p>
    <p><strong>Time:</strong> [Insert Time]</p>
    <p><strong>Venue:</strong> [Insert Venue Name, Address]</p>
    <p>Please arrive 30 minutes early. Dress code: [Formal/Semi-Formal/Other]</p>
  </section>

  <section>
    <h2>Reception</h2>
    <p>Join us after the ceremony for dinner, dancing, and celebration!</p>
    <p><strong>Reception Venue:</strong> [Insert Reception Details]</p>
  </section>

  <section>
    <h2>RSVP</h2>
    <form class="rsvp-form" action="https://formspree.io/f/your-form-id" method="POST">
      <input type="text" name="name" placeholder="Your Full Name" required />
      <input type="email" name="email" placeholder="Email Address" required />
      <select name="attendance" required>
        <option value="">Will you attend?</option>
        <option value="yes">Yes, can't wait!</option>
        <option value="no">Sorry, can't make it</option>
      </select>
      <textarea name="message" placeholder="Any dietary needs or a message for us?" rows="4"></textarea>
      <button type="submit">Send RSVP</button>
    </form>
  </section>

  <footer>
    <p>With love, Chrissy & [Partner's Name] — © 2025</p>
  </footer>

</body>
</html>
