# NamedParameters-JavaScript

How to Use Named Parameters in JavaScript

function example({ arg1 = 1, arg2 = 2, arg3 = 3 } = {}) {
  return { arg1, arg2, arg3 };
}

example({ arg2: 4, arg1: 2 }); // { arg1: 2, arg2: 4, arg3: 3 }

example(); // { arg1: 1, arg2: 2, arg3: 3 }

Sources:
https://masteringjs.io/tutorials/fundamentals/parameters#:~:text=JavaScript%2C%20by%20default%2C%20does%20not,have%20default%20values%20set%20up.
