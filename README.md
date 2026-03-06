# QA-DSA---25--Recursion-Factorial

function factorial(n) {
  // your solution here
  if (typeof n !== 'number' || !Number.isFinite(n) || n < 0) {
    return false;
  }
  if (n == 0) {
    return 1
  }
  return n * factorial(n - 1)
}

module.exports = { factorial };
