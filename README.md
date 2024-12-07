# React 19 useEffect setInterval Memory Leak

This repository demonstrates a common error in React 19 involving the `useEffect` hook and `setInterval`.  Improperly handling the cleanup function in `useEffect` when using `setInterval` can lead to memory leaks. The provided solution shows the correct way to implement this.