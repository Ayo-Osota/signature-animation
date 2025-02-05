# Signature Animation

A React component for animating handwriting using SVG paths.

## Features

- Animate handwritten signatures or letters using SVG.
- Lightweight and easy to integrate into any React project.

![Frontend_System_Design_Questions__Toast_Component___HLD_LLD](https://github.com/piyush-eon/react-toast-popup/assets/51760520/be023ecf-39fb-4cb0-beeb-98519050ba99)

## Installation

```jsx
npm install signature-animation
```

or using yarn:

```jsx
yarn add signature-animation
```

## Usage

```jsx
import React from "react";
import SignatureAnimation from "signature-animation";

function App() {
  return (
    <div>
      <h1>Signature Animation Demo</h1>
      <SignatureAnimation>Hello</SignatureAnimation>
    </div>
  );
}

export default App;
```

#### Animations

You can specify an animation type for the notifications. The available animations are:

- "fade"
- "pop"
- "slide"

```jsx
triggerNotification({
  type: "success",
  message: "This is a success message with a pop animation!",
  duration: 3000,
  animation: "pop",
});
```

## Props

| Prop      | Type   | Default   | Description                           |
| --------- | ------ | --------- | ------------------------------------- |
| children  | string | `"Hello"` | The text to animate as handwriting.   |
| className | string | `""`      | Custom class for styling.             |
| duration  | number | `1.5`     | Duration of the animation in seconds. |

```jsx
git clone https://github.com/Ayo-Osota/signature-animation.git
cd signature-animation
npm install
npm run build
```

## License

This project is licensed under the MIT License.
