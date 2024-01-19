# This is a Promise Project for testing purpose.

<br>
There are 6 static methods of Promise class:<br>
<bold>1.</bold>Promise.all(promises) – waits for all promises to resolve and returns an array of their results. If any of the given promises rejects, it becomes the error of Promise.all, and all other results are ignored.
<br>
<bold>2.</bold>Promise.allSettled(promises) (recently added method) – waits for all promises to settle and returns their results as an array of objects with:
status: "fulfilled" or "rejected"
value (if fulfilled) or reason (if rejected).
<br>
<bold>3.</bold>Promise.race(promises) – waits for the first promise to settle, and its result/error becomes the outcome.
<br>
<bold>4.</bold>Promise.any(promises) (recently added method) – waits for the first promise to fulfill, and its result becomes the outcome. If all of the given promises are rejected, AggregateError becomes the error of Promise.any.
<br.>
<bold>5.</bold>Promise.resolve(value) – makes a resolved promise with the given value.
<br>
<bold>6.</bold>Promise.reject(error) – makes a rejected promise with the given error.
