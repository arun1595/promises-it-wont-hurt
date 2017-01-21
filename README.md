# Promise - It won't hurt

This repo hosts my solutions for the [NodeSchool](https://nodeschool.io) workshopper [Promise - It won't hurt](https://github.com/stevekane/promise-it-wont-hurt)

### 1. Warmup
  For this first lesson, let’s review what we already know about asynchronous
  operations in JavaScript.

  Using `setTimeout`, print the string `'TIMED OUT!'` after 300ms.

  [Solution](warmup.js)

### 2. Fulfill a promise
  Create a promise. Have it fulfilled with a value of `'FULFILLED!'` in executor after a delay of 300ms, using `setTimeout`.

  Then, print the contents of the promise after if has been fulfilled by passing `console.log` to then.

  **Boilerplate**

    'use strict';
    var promise = new Promise(function (fulfill, reject) {
      // Your solution here
    });

  [Solution](setTimeoutPromise.js)

### 3. Reject a promise

  Create a promise that after a delay of 300ms, rejects with an `Error` object.
  The Error object should be constructed with parameter `'REJECTED!'`, which is the textual message of the error.

  Create a function onReject to print `error.message` using `console.log`. Pass this function as a rejection handler to the then method of your promise.

  [Solution](rejectPromise.js)