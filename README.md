# Silent Crash on Data Fetch in React Native

This repository demonstrates a subtle bug in React Native data fetching that can lead to silent crashes without clear error messages in the console. The code fetches data from a remote API and renders it in a FlatList. The issue is intermittent, sometimes working as expected, sometimes crashing without any visible error to the user or developer.

## Steps to Reproduce

1. Clone the repository.
2. Run the app on an emulator or device.
3. Observe the inconsistent behavior – sometimes the data loads, sometimes the app crashes silently.

## Solution
The solution involves properly handling promise rejections and implementing robust error handling.  The improved error handling provides more context and makes debugging simpler.