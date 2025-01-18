# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React applications involving the `useEffect` hook.  The provided code exhibits an infinite loop due to improper use of the dependency array. The solution showcases how to resolve the issue by correctly specifying dependencies.

## Bug
The `bug.js` file contains a component that uses `useEffect` without a dependency array. This causes the effect to run after every render, triggering an endless cycle of re-renders, resulting in an infinite loop.

## Solution
The `bugSolution.js` file corrects the issue by adding an empty dependency array `[]` to `useEffect`. This ensures the effect runs only once after the initial render, resolving the infinite loop problem.
