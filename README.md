# React useEffect Hook with Empty Dependency Array Issue

This repository demonstrates a common issue encountered when using the `useEffect` hook in React with an empty dependency array.  The expectation is that the effect within the `useEffect` runs only once when the component mounts. However, in this specific scenario, the console log statement is not appearing in the browser's console.

## Problem
The provided code intends to log 'Mounted!' to the console only once when the component initially renders.  Despite the empty dependency array `[]`, this doesn't happen.

## Solution
The solution involves ensuring that the `useEffect` hook is properly used and that there are no unexpected side effects that might be preventing the log statement from executing.  See `bugSolution.js` for the fix.