<!DOCTYPE html>
<html>
<head>
  <title>What's your Favorite Black?</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <h1 id="title">What's your Favorite Black?</h1>
  <p id="description">Please fill out the form below <3</p>

  <form id="survey-form">
    <label for="name" id="name-label">Name:</label>
    <input type="text" id="name" placeholder="Enter your name" required>

    <label for="email" id="email-label">Email:</label>
    <input type="email" id="email" placeholder="Enter your email" required>

    <label for="number" id="number-label">Number:</label>
    <input type="number" id="number" placeholder="Enter a number" min="1" max="100" required>

    <label for="dropdown">Select an option:</label>
    <select id="dropdown">
      <option value="option1">Matte Black</option>
      <option value="option2">Satin Black</option>
      <option value="option3">Velvet Black</option>
    </select>

    <fieldset>
      <legend>Choose an option:</legend>
      <label>
        <input type="radio" name="radio-group" value="option1"> Matte Black
      </label>
      <label>
        <input type="radio" name="radio-group" value="option2"> Satin Black
      </label>
      <label>
        <input type="radio" name="radio-group" value="option3"> Velvet Black
      </label>
    </fieldset>

    <fieldset>
      <legend>Choose one or more options:</legend>
      <label>
        <input type="checkbox" name="checkbox-group" value="checkbox1"> Marble Black
      </label>
      <label>
        <input type="checkbox" name="checkbox-group" value="checkbox2"> Paper Black
      </label>
      <label>
        <input type="checkbox" name="checkbox-group" value="checkbox3"> Stone Black
      </label>
    </fieldset>

    <label for="comments">Additional comments:</label>
    <textarea id="comments" placeholder="Enter your comments"></textarea>

    <button type="submit" id="submit">Submit</button>
  </form>
</body>
</html>
