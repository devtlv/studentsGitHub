# Asynchronous JavaScript Quiz

**Last Updated**: 20/03/2024

## Question 1

- What is the purpose of Promises in JavaScript?
  - a) To handle synchronous tasks
  - b) To handle asynchronous tasks
  - c) To define classes and objects
  - d) To perform mathematical calculations  
    **Correct Answer:** b) To handle asynchronous tasks

---

## Question 2

- Which HTTP method is typically used to send data to a server in JavaScript?
  - a) GET
  - b) POST
  - c) PUT
  - d) DELETE  
    **Correct Answer:** b) POST

---

## Question 3

- What is the event loop in JavaScript responsible for?
  - a) Managing asynchronous operations
  - b) Handling errors in synchronous code
  - c) Manipulating the DOM
  - d) Creating animations  
    **Correct Answer:** a) Managing asynchronous operations

---

## Question 4

- Which method is used to execute a function after a specified time interval?
  - a) delay()
  - b) executeAfter()
  - c) setTimeout()
  - d) setTimer()  
    **Correct Answer:** c) setTimeout()

---

## Question 5

- In JavaScript, what does the Promise.all method do?
  - a) Executes all promises in parallel and returns an array of their results
  - b) Executes promises sequentially and returns the result of the first resolved promise
  - c) Executes all promises in parallel and returns the result of the last resolved promise
  - d) Executes promises sequentially and returns an array of their results  
    **Correct Answer:** a) Executes all promises in parallel and returns an array of their results

---

## Question 6

- What is the purpose of error handling in asynchronous JavaScript?
  - a) To prevent errors from occurring
  - b) To gracefully handle errors that may occur during asynchronous operations
  - c) To terminate the program when an error occurs
  - d) To ignore errors and continue execution  
    **Correct Answer:** b) To gracefully handle errors that may occur during asynchronous operations

---

## Question 7

- Which method is used to fetch resources asynchronously from a server in JavaScript?
  - a) get()
  - b) fetch()
  - c) request()
  - d) retrieve()  
    **Correct Answer:** b) fetch()

---

## Question 8

- What is the purpose of AJAX in web development?
  - a) To create animations
  - b) To manipulate the DOM
  - c) To fetch data asynchronously from a server without reloading the page
  - d) To handle synchronous tasks  
    **Correct Answer:** c) To fetch data asynchronously from a server without reloading the page

---

## Question 9

- What is the purpose of the Content-Type header in an HTTP request?
  - a) To specify the character encoding of the request
  - b) To specify the type of data being sent in the request body
  - c) To specify the HTTP method used in the request
  - d) To specify the type of authentication used for the request
    **Correct Answer:** b) To specify the type of data being sent in the request body

---

## Question 10

- Which method is used to repeat execution at specified intervals?
  - a) repeatInterval()
  - b) setInterval()
  - c) setRepeat()
  - d) executeEvery()  
    **Correct Answer:** b) setInterval()

---

## Question 11

- How would you refactor the following function to introduce asynchronous behavior in JavaScript?

```javascript
function myFunction() {
  // function body
}
```

- a) Add the keyword `async` before the function declaration
- b) Wrap the function body in a `setTimeout` function
- c) Use the `await` keyword within the function
- d) Replace the function declaration with an arrow function
  **Correct Answer:** a) Add the keyword `async` before the function declaration

---

## Question 12

- Which of the following is NOT a state of a Promise in JavaScript?
- a) Pending
- b) Fulfilled
- c) Resolved
- d) Rejected  
   **Correct Answer:** c) Resolved

---

## Question 13

- How would you modify the following code to handle errors gracefully in asynchronous JavaScript?

```javascript
async function fetchData(url) {
  const response = await fetch(url);
  const data = await response.json();
  return data;
}
```

- a) Use the catch method on the response object to handle errors returned from the fetch operation.
- b) Implement a callback function to handle errors returned from the asynchronous operation.
- c) Wrap the function body in a try...catch block to catch any errors that may occur during asynchronous execution.
- d) Prefix the function declaration with the async keyword to automatically handle errors in asynchronous functions.

**Correct Answer:** c) Wrap the function body in a try...catch block to catch any errors that may occur during asynchronous execution.

---

## Question 14

- What is the purpose of the await keyword in JavaScript?
  - a) To stop the execution of a function
  - b) To pause the execution until a promise is resolved
  - c) To cancel asynchronous operations
  - d) To execute code synchronously  
    **Correct Answer:** b) To pause the execution until a promise is resolved

---

## Question 15

- Which method is used to execute a function repeatedly with a fixed time delay between each execution?
  - a) setInterval()
  - b) delay()
  - c) setDelay()
  - d) repeat()  
    **Correct Answer:** a) setInterval()

---

## Question 16

- What does the following code snippet demonstrate?
  ```javascript
  const data = { name: "John", age: 30 };
  const json = JSON.stringify(data);
  ```
  - a) Parses a JSON string into a JavaScript object
  - b) Converts a JavaScript object into a JSON string
  - c) Executes an asynchronous operation
  - d) Fetches data from a server using AJAX
    **Correct Answer:** b) Converts a JavaScript object into a JSON string

---

## Question 17

- What does the following code snippet achieve?

  ```javascript
  async function fetchData(url) {
    const response = await fetch(url);
    if (!response.ok) {
      throw new Error("Failed to fetch data");
    }
    const data = await response.json();
    return data;
  }
  ```

  - a) Fetches data synchronously from a URL and handles errors using try...catch.
  - b) Fetches data asynchronously from a URL and throws an error if the response is not successful.
  - c) Fetches data asynchronously from a URL and ignores any errors that occur during the process.
  - d) Fetches data synchronously from a URL and returns it as a JSON object.

    **Correct Answer:** b) Fetches data asynchronously from a URL and throws an error if the response is not successful.

---

## Question 18

- What is JSON in JavaScript?

  - a) A built-in method for creating random data
  - b) A data interchange format
  - c) A method for manipulating the DOM
  - d) A method for creating asynchronous functions
    **Correct Answer:** b) A data interchange format

---

## Question 19

- What does the reject method do in a Promise object?
  - a) Marks the promise as fulfilled with a value
  - b) Marks the promise as rejected with a reason
  - c) Marks the promise as pending
  - d) Marks the promise as resolved  
    **Correct Answer:** b) Marks the promise as rejected with a reason

---

## Question 20

- What does the resolve method do in a Promise object?
  - a) Marks the promise as fulfilled with a value
  - b) Marks the promise as rejected with a reason
  - c) Marks the promise as pending
  - d) Marks the promise as resolved  
    **Correct Answer:** a) Marks the promise as fulfilled with a value

---

## Question 21

- What is the primary purpose of asynchronous behavior in JavaScript?
  - a) To improve code readability and maintainability.
  - b) To execute code sequentially to ensure predictable outcomes.
  - c) To handle time-consuming operations without blocking the main thread.
  - d) To enforce strict error handling and prevent runtime exceptions.
    **Correct Answer:** c) To handle time-consuming operations without blocking the main thread.

---

## Question 22

- Which method is used to resolve multiple promises at once?
  - a) Promise.all()
  - b) Promise.race()
  - c) Promise.resolveAll()
  - d) Promise.waitAll()  
    **Correct Answer:** a) Promise.all()

---

## Question 23

- What is the purpose of the Promise.race method?
  - a) To wait for all promises to be resolved
  - b) To reject as soon as one of the promises is resolved or rejected
  - c) To resolve as soon as one of the promises is resolved or rejected
  - d) To execute promises sequentially  
    **Correct Answer:** c) To resolve as soon as one of the promises is resolved or rejected

---

## Question 24

- What is the purpose of the Fetch API in JavaScript?
  - a) To manipulate the DOM
  - b) To handle errors in asynchronous operations
  - c) To fetch resources asynchronously from a server
  - d) To execute functions asynchronously  
    **Correct Answer:** c) To fetch resources asynchronously from a server
