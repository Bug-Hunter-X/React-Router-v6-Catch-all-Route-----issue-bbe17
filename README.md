# React Router v6 Catch-all Route '*' Issue

This repository demonstrates a common issue encountered when using the catch-all route ('*') in React Router v6. The catch-all route, intended to handle unmatched routes and display a 404 page, sometimes fails to work as expected.  This example shows the issue and a solution.

## Problem
The provided `App.js` demonstrates how a catch all route may fail to catch routes not explicitly defined.

## Solution
The `AppSolution.js` provides a solution to this issue by ensuring that the catch-all route is positioned correctly within the `Routes` component to function correctly.