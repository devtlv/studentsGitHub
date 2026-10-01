### Solution WEEK 6 REMOTE LEARNING Exercise Advanced Functions

```javascript
// Higher-order function: operateOnArray
function operateOnArray(array, func) {
  return array.map(func);
}

// Test functions
function double(num) {
  return num * 2;
}

function square(num) {
  return num * num;
}

function sum(numbers) {
  return numbers.reduce((acc, curr) => acc + curr, 0);
}

// Test cases
const numbers = [1, 2, 3, 4, 5];

// Double each number
const doubledNumbers = operateOnArray(numbers, double);
console.log("Doubled Numbers:", doubledNumbers);

// Square each number
const squaredNumbers = operateOnArray(numbers, square);
console.log("Squared Numbers:", squaredNumbers);

// Calculate the sum of all numbers
const totalSum = sum(operateOnArray(numbers, (num) => num));
console.log("Total Sum:", totalSum);
```

### Solution WEEK 6 REMOTE LEARNING Exercise HTTP

### Exercise: Interactive Form Submission

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Interactive Form Submission</title>
<script>
  function handleSubmit(event) {
    event.preventDefault(); // Prevent default form submission behavior

    // Extract form data
    const formData = new FormData(event.target);
    const name = formData.get('name');
    const email = formData.get('email');
    const message = formData.get('message');

    // Simulate form submission (you can replace this with actual AJAX requests)
    console.log('Submitted Data:');
    console.log('Name:', name);
    console.log('Email:', email);
    console.log('Message:', message);

    // Display confirmation message
    const confirmation = document.getElementById('confirmation');
    confirmation.textContent = 'Thank you for your feedback!';
  }
</script>
</head>
<body>
<h2>Submit Feedback</h2>
<form id="feedbackForm" method="post" action="#" onsubmit="handleSubmit(event)">
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name" required><br>
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email" required><br>
  <label for="message">Feedback Message:</label><br>
  <textarea id="message" name="message" rows="4" required></textarea><br>
  <button type="submit">Submit</button>
</form>
<p id="confirmation"></p>
</body>
</html>
```
