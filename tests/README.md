# Regression tests

Use Node.js 18.8 or newer, then run `npm install` and `npm test`.

The tests load the actual TypeScript provider through Vite and render it with
React's test renderer. Fetch responses are controlled locally; no live YTS API
connection or browser download is required. Search tests wait for the existing
500 ms debounce.
