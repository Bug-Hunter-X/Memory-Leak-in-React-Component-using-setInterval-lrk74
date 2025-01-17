# React setInterval Memory Leak

This repository demonstrates a common mistake in React components: using `setInterval` within `useEffect` without proper cleanup.  This leads to a memory leak because the interval continues to run even after the component unmounts.

The `bug.js` file contains the flawed component, while `bugSolution.js` provides the corrected version.