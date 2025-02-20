# Nested Routes Issue in React Router v6

This repository demonstrates a common issue encountered when working with nested routes in React Router v6.  The main issue is that nested routes are not rendering as expected. The parent route renders successfully, but its child routes fail to display.  The solution addresses this problem by illustrating a correct implementation of nested routes using React Router v6's `Routes` and `Route` components.

## Bug Description

The original `App.js` demonstrates a flawed implementation of nested routes. This leads to the nested routes being ignored and preventing them from rendering.

## Solution

The `AppSolution.js` file provides a corrected version of nested route implementation. This corrected implementation uses the `Routes` and `Route` components correctly, ensuring the correct route matching and rendering.