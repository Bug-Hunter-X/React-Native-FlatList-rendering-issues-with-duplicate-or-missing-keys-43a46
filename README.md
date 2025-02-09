# React Native FlatList Key Extraction Error

This repository demonstrates a common error in React Native's FlatList component: incorrect or missing `keyExtractor` functions.  The `keyExtractor` function is essential for ensuring that FlatList renders items correctly and efficiently.  Failure to provide a proper `keyExtractor` can lead to unexpected UI behavior, including duplicated items, incorrect item updates, and performance issues. 

The `bug.js` file showcases the problematic code, while `bugSolution.js` demonstrates the solution.  This example highlights the importance of providing a unique key for each item in your FlatList data source.