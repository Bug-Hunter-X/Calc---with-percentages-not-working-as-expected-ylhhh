# CSS calc() with percentages bug

This repository demonstrates a bug where the CSS `calc()` function produces unexpected results when used with percentages.  The expected behavior is not observed, leading to layout issues. The solution demonstrates a workaround to achieve the intended result.

## Bug Description

When using `calc()` with percentages to calculate widths or other properties, the final calculated value might be incorrect. This is especially noticeable when dealing with nested elements or complex calculations involving percentages.

## Solution

The solution may involve using different units (like pixels or ems) within `calc()` instead of percentages, or a complete restructuring of the CSS depending on what you need to achieve.