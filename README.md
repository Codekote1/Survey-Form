# Survey-Form
<!DOCTYPE html>
<html>
<head>
  <title>Survey form</title>
  <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1 id="title">Survey Form</h1>
    <p id="description">please fill out survey form.</p>
    <form id="survey-form">
      <label for ="name"id='name-label'>Name:</label>
<input type="text" id="name" placeholder="Enter your name"required>
<label for "email" id="email-label">Email:</label>
<input type="email" id="email"placeholder="Enter your email"required>
<label for="number" id="number-label">Number:</label>
<input type="number" id="number"placeholder="Enter a number between 1 and 10" min="1" max="10"required>
<label for="dropdown">Select an option:</label>
<select id="dropdown"required>
    <option value="">Select an option</option>
			<option value="option1">Option 1</option>
			<option value="option2">Option 2</option>
		</select>
<label>Choose an option:</label>
<input type="radio" name="radio-group" value="option1" required>Option 1
<input type="radio" name="radio-group" value="option2" required>Option 2
<label>Choose all that apply:</label>
<input type="checkbox" name="checkbox-group" value="option1" required>Option 1
<input type="checkbox" name="checkbox-group" value="option2" required>option 2
<textarea placeholder="Enter your comments here"></textarea>
<button type="submit" id="submit">Submit</button>
</form>
    </body>
    </html>
