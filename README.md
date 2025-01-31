# Asynchronous Prop Updates Break Navigate in React Router v6

This repository demonstrates a bug in React Router v6 where the `Navigate` component doesn't reroute correctly when conditionally rendered and its condition depends on a prop that updates asynchronously.  The issue occurs because the `Navigate` component is rendered, and then the prop changes, not triggering a re-render or navigation.

## Setup

1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.

## Steps to Reproduce

1. Observe the initial route.
2. Notice how the asynchronous data update does not trigger a navigation. 
3. The solution file illustrates a proper way to address the issue.