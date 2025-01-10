# React useEffect Cleanup Function Bug

This repository demonstrates a common React bug related to the `useEffect` hook.  The provided `MyComponent` uses `setInterval` to update a counter, but fails to clear the interval when the component unmounts, potentially leading to memory leaks and unexpected behavior.  The solution demonstrates the correct way to use `useEffect` with cleanup functions to avoid this issue.  

**Bug:** Missing cleanup in useEffect, causing memory leaks.

**Solution:** Using cleanup function in useEffect to clear the interval before component unmounts. 

Refer to `bug.js` and `bugSolution.js` for code samples.