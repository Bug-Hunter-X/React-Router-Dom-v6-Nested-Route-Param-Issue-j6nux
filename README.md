# React Router v6 Nested Route Parameter Bug

This repository demonstrates a bug encountered when using nested routes and parameters in React Router v6. The issue occurs when a specific route containing a parameter is added. This causes unexpected behavior, such as crashes or incorrect rendering.

## Bug Description

The bug manifests as an unexpected rendering error when navigating to a route that uses parameters. The application might crash or simply not render the correct component.

## Solution

The solution involves carefully examining the route configuration and ensuring correct usage of parameters and nested routes in `react-router-dom` v6. The provided solution demonstrates how to resolve this problem.  Check `bugSolution.js` for a working implementation.