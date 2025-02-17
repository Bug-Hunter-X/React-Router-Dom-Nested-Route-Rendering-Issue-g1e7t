# React Router Dom Nested Route Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6.  The problem involves the unexpected rendering behavior of child routes within a parent route.

## Problem Description:

When navigating to a nested route, the child component may not render as expected, despite the route seemingly being correctly defined. This often manifests as either the parent component rendering instead of the child, or a blank screen.

## Solution:

The solution involves carefully reviewing the route structure and ensuring that the nesting is correct and follows the rules of React Router.  In this case, it is crucial to use the `Outlet` component within the parent route to render the child routes.