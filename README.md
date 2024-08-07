# Exercise: JavaScript Async Functions

![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

### This is a project for Front-End Technologies May 2024 Course @ SoftUni
---

1. [Exercise: JavaScript Async Functions I](#exercise-javascript-async-functions-i)
    1. [Hello World](#hello-world)
    2. [Chained Promises](#chained-promises)
    3. [Simple Promise](#simple-promise)
    4. [Promise Rejection](#promise-rejection)
    5. [Promise with Multiple Handlers](#promise-with-multiple-handlers)
    6. [Promise All](#promise-all)
    7. [Promise Race](#promise-race)
    8. [Async Function with Await](#async-function-with-await)
    9. [Async Function with Error Handling](#async-function-with-error-handling)
    10. [Chained Promises with Async/Await](#chained-promises-with-asyncawait)
    11. [Quiz](#quiz)
    12. [Simple Stopwatch](#simple-stopwatch)
    13. [Countdown Timer](#countdown-timer)
    14. [Sum Even Numbers in Background](#sum-even-numbers-in-background)
    15. [Simple Text Adventure Game](#simple-text-adventure-game)
2. [Exercise: JavaScript Async Functions II](#exercise-javascript-async-functions-ii)
    1. [Simulating Network Request with Fetch](#simulating-network-request-with-fetch)
    2. [Handling Fetch Errors](#handling-fetch-errors)
    3. [Parallel Fetch Requests](#parallel-fetch-requests)
    4. [Sequential Fetch Requests](#sequential-fetch-requests)
    5. [Multiple Promises](#multiple-promises)
    6. [Retrying a Failed Promise](#retrying-a-failed-promise)
    7. [Throttling Promises](#throttling-promises)
    8. [Timeout for Fetch Requests](#timeout-for-fetch-requests)
    9. [Async Function with Error Handling](#async-function-with-error-handling)
    10. [Combining Async/Await with Generators](#combining-asyncawait-with-generators)

## Exercise: JavaScript Async Functions I

### Hello World
Function `helloWorld()`, using `setTimeout` with callbacks, which logs two messages to the console with a time delay between them.
- **Requirements**
  - Log "Hello" immediately.
  - Log "World" after a 2-second delay.

### Chained Promises
Function `chainedPromises()`, using `setTimeout` with callbacks, which logs a series of messages to the console with increasing delays.
- **Requirements**
  - Log "Start" immediately.
  - Log "1" after 1 second.
  - Log "2" after 2 seconds.
  - Log "3" after 3 seconds.

### Simple Promise
Function `simplePromise()` which creates a promise that resolves to "Success!" after 2 seconds and logs the result.
- **Requirements**
  - The promise resolves to "Success!" after 2 seconds.
  - Log "Success!" to the console.

### Promise Rejection
Function `promiseRejection()` which creates a promise that rejects with an error message after 1 second and logs the error.
- **Requirements**
  - The promise rejects with "Something went wrong!" after 1 second.
  - Log the error message.

### Promise with Multiple Handlers
Function `promiseWithMultipleHandlers()` which creates a promise that resolves to "Hello World" after 2 seconds and logs the message twice using multiple `.then` handlers.
- **Requirements**
  - The promise resolves to "Hello World" after 2 seconds.
  - Log "Hello World" twice.

### Promise All
Function `allPromise()`, using `Promise.all` that creates three promises that resolve after 1, 2, and 3 seconds respectively and logs all results together when they are all resolved.
- **Requirements**
  - Create three promises with specified delays.
  - Use `Promise.all` to wait for all promises to resolve.
  - Log all results together.

### Promise Race
Function `racePromise()`, using `Promise.race` which creates three promises that resolve after 1, 2, and 3 seconds respectively and logs the first resolved result.
- **Requirements**
  - Create three promises with specified delays.
  - Use `Promise.race` to log the first resolved result.

### Async Function with Await
Async function `simplePromiseAsync()` that waits for 2 seconds and then logs "Async/Await is awesome!"
- **Requirements**
  - Create an async function.
  - Use `await` to wait for 2 seconds.
  - Log the message after the delay.

### Async Function with Error Handling
Async function `promiseRejectionAsync()` which throws an error and catches it, logging the error message.
- **Requirements**
  - Create an async function that throws an error.
  - Catch the error and log the message.

### Chained Promises with Async/Await
Async function `chainedPromisesAsync()` that waits for three promises that resolve after 1, 2, and 3 seconds respectively and logs their results in order.
- **Requirements**
  - Create an async function.
  - Wait for three promises with specified delays.
  - Log the results in order.

### Quiz
Simple quiz game that runs in the console. The game will ask questions, accept user input, and provide feedback.
- **Requirements**
  - Use promises and async/await for asynchronous operations.
  - Display questions and possible answers.
  - Accept user input and provide feedback.
  - Tally the score and display the result.

### Simple Stopwatch
Creates a simple stopwatch that starts counting elapsed time in seconds when the "Start Stopwatch" button is clicked and stops when the "Stop Stopwatch" button is clicked.
- **Requirements**
  - Start counting when the "Start Stopwatch" button is clicked.
  - Display elapsed time every second in the console.
  - Stop counting when the "Stop Stopwatch" button is clicked.
  - Reset elapsed time when stopped.

### Countdown Timer
Creates a countdown timer that starts from a specified number of seconds when the "Start Countdown" button is clicked.
- **Requirements**
  - Start countdown from input number of seconds.
  - Display remaining time every second in the console.
  - Stop when the timer reaches zero and display a finished message.
  - Save remaining time asynchronously when countdown finishes.

### Sum Even Numbers in Background
Calculates the sum of all even numbers in the range from 1 to 1,000,000,000 without blocking the console interface.
- **Requirements**
  - Start calculation when the "Start Calculation" button is clicked.
  - Enable user input for commands while calculating.
  - Print the current sum with the "show" command.
  - Stop calculation with the "exit" command.

### Simple Text Adventure Game
Creates a text-based adventure game that guides the player through choices leading to different outcomes.
- **Requirements**
  - Start game with the "Start Adventure" button.
  - Prompt player for choices using `prompt` function.
  - Provide feedback based on player's decisions.
  - Include simulated delays using promises and `setTimeout`.
  - Handle different scenarios and allow player to restart or end the game.

## Exercise: JavaScript Async Functions II

### Simulating Network Request with Fetch
Function `fetchData()` which fetches data and logs the JSON response.
- **Requirements**
  - Use the fetch API to get data.
  - Parse the response as JSON.
  - Log the JSON response to the console.

### Handling Fetch Errors
Function `fetchDataWithErrorHandling()` which fetches data and handles potential errors using try/catch.
- **Requirements**
  - Use the fetch API to get data.
  - Handle errors using try/catch.
  - Log the JSON response or any errors.

### Parallel Fetch Requests
Function `fetchParallel()` which makes two parallel fetch requests and logs both results.
- **Requirements**
  - Make two parallel fetch requests.
  - Use Promise.all to handle the responses.

### Sequential Fetch Requests
Function `fetchSequential()` which makes two sequential fetch requests and logs both results.
- **Requirements**
  - Make two sequential fetch requests.
  - Log each result after it is received.

### Multiple Promises
Function `multiplePromises()` which creates three promises where one resolves after 1 second, one resolves after 2 seconds, and one rejects after 3 seconds. Log the status and value or reason for each promise when all are settled.
- **Requirements**
  - Create three promises with specified delays.
  - Use Promise.allSettled to handle all promises.
  - Log the status and value or reason for each promise.

### Retrying a Failed Promise
Function `startRetry()` which creates a function that retries a promise up to 3 times if it fails. If the promise eventually resolves, log the result. If it fails after all retries, log the error.
- **Requirements**
  - Create a function that retries a promise up to 3 times.
  - Log the result if the promise resolves.
  - Log the error if the promise fails after all retries.

### Throttling Promises
Function `throttlePromises()` which creates a function that throttles promises so that only two promises are executed in parallel at any time. Ensure that once a promise is resolved, the next one starts.
- **Requirements**
  - Create a function that throttles promises with a specified concurrency limit.
  - Ensure that only two promises are executed in parallel at any time.
  - Log the results after all promises are resolved.

### Timeout for Fetch Requests
Function `fetchWithTimeout()` that fetches data from a URL with a timeout. If the fetch takes longer than the timeout, it should reject.
- **Requirements**
  - Create a function that fetches data with a specified timeout.
  - Reject the promise if the fetch takes longer than the timeout.
  - Log the result or error.

### Async Function with Error Handling
Class `AsyncQueue()` which creates a queue that processes asynchronous tasks one by one in sequence.
- **Requirements**
  - Create a queue that processes asynchronous tasks in sequence.
  - Ensure the tasks are processed one by one.
  - Log the completion of each task.

### Combining Async/Await with Generators
Function `startAsyncGenerator()` that combines async/await with generators to handle a sequence of asynchronous tasks.
- **Requirements**
  - Create a function that combines async/await with generators.
  - Ensure the function can handle a sequence of asynchronous tasks.
  - Log the results of the tasks.

## Contributing
Contributions are welcome! If you have any improvements or bug fixes, feel free to open a pull request.

## License
This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, please open an issue in the repository.
