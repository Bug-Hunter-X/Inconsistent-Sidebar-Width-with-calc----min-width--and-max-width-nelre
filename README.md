# Inconsistent Sidebar Width with CSS calc(), min-width, and max-width

This repository demonstrates an uncommon issue related to using `calc()` in CSS with percentages and `min-width`/`max-width`. The goal is to create a sidebar with a width of 20% of the viewport, but with minimum and maximum width constraints.

## Problem

The provided CSS uses `calc()` to compute the sidebar's width, intending to ensure it respects the `min-width` and `max-width` properties. However, the behavior can be inconsistent across different browsers and viewport sizes.

## Solution

The solution involves a more robust approach to calculating the sidebar's width, utilizing media queries to handle different viewport sizes effectively and avoiding the problematic direct use of `calc()` with `min-width` and `max-width`.