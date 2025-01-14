# CSS `calc()` function and undefined parent width

This repository demonstrates a common issue with CSS's `calc()` function: unexpected results when the parent element's width is not explicitly set.

## Problem

The CSS `calc()` function is powerful for dynamic calculations, but it relies on the context of the parent element. If the parent doesn't have a specified width, the calculation might be inaccurate or fail completely.

## Solution

The solution involves ensuring that the parent element has a defined width using techniques such as setting a fixed width, using `width: 100vw;` (viewport width), or other layout techniques that guarantee a consistent parent width.