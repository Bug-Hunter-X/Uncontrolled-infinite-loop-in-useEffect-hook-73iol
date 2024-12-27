# Uncontrolled Infinite Loop in React's useEffect Hook

This repository demonstrates a common React bug: an uncontrolled infinite loop caused by an improperly used `useEffect` hook. The example shows how omitting the dependency array in `useEffect` leads to an infinite re-render cycle. The solution showcases how to correctly utilize the dependency array to prevent this issue.