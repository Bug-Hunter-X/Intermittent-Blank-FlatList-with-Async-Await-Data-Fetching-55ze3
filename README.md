# Intermittent Blank FlatList in React Native with Async/Await

This repository demonstrates a bug where a React Native `FlatList` component intermittently renders blank when fetching data asynchronously using `async/await`. The issue is difficult to reproduce consistently, but appears to be related to timing and data handling within the `useEffect` hook.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install` or `yarn install`.
3. Run the app on a device or emulator. 
4. Observe that the FlatList will sometimes be blank (no data) and other times display the expected data. 

## Bug Analysis and Solution

The root cause is likely an improper handling of the component's state during the asynchronous data fetching process.  The provided solution addresses this.