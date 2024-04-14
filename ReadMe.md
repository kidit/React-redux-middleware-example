
# React Project Setup Guide

## 1. Prepare the Work Environment

### 1-1. Create a new React application:
```bash
yarn create react-app learn-redux-middleware
```

### 1-2. Add React Redux and React Actions:
```bash
yarn add react-redux react-actions
```

### 1-3. Add Redux Logger:
```bash
yarn add redux-logger
```

### 1-4. Add Redux Thunk Middleware:
```bash
yarn add redux-thunk
```

### 1-5. Setup Fake API Access:
- **Read Post**: [https://jsonplaceholder.typicode.com/posts/:id](https://jsonplaceholder.typicode.com/posts/:id)
- **Read All User Information**: [https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users)

### 1-6. Add Axios for HTTP Requests:
```bash
yarn add axios
```

### 1-7. Add Redux Saga:
```bash
yarn add redux-saga
```

### 1-8. Add Redux Extension DevTool Library:
```bash
yarn add redux-devtools-extension
```

## 2. App.js Code Description

### 2-1. Counter Component:
Import `CounterContainer` from `./containers/CounterContainer`. Implement a function where the number goes up or down when you press the button.

### 2-2. Sample API Component:
Import `SampleContainer` from `./containers/SampleContainer`. This component uses the API addresses provided in section 1-5 to display data.

### Usage in App.js:
Include `<CounterContainer/>` and `<SampleContainer/>` inside `<div>` tags to check their functionality.

---

This file provides a comprehensive guide on setting up and running the example React project as described in the textbook.
