# Unhandled Runtime Error in Next.js 15 Page Component

This repository demonstrates a runtime error that can occur in Next.js 15 when accessing a non-existent variable within a page component. The error is not gracefully handled, resulting in a crash of the application.  The solution shows how to implement error boundaries to handle such issues.

## Problem

In `pages/about.js`, we attempt to access a variable (`nonExistentVariable`) that has not been defined. This results in a runtime error that is not handled by Next.js, leading to a crash.

## Solution

The solution involves using React's error boundaries to catch and handle the error.  This prevents the app from crashing and allows for a more graceful user experience.  The solution shows how to implement this using the `ErrorBoundary` component. 