# HTML Attribute Case Sensitivity Bug

This repository demonstrates a subtle but important bug in HTML: the incorrect use of casing for attribute values.  While browsers often handle it gracefully, it's not valid HTML and can cause issues in certain scenarios.

The `bug.html` file showcases the problematic code, while `bugSolution.html` provides the corrected version.

## Bug Description

HTML attributes are not always case-sensitive, but using inconsistent casing (e.g., using `TYPE` instead of `type`) is considered bad practice and can cause unexpected behaviour in some browsers or validation tools.  This bug highlights the importance of using consistent lowercase for HTML attributes to ensure proper rendering and validation.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` and `bugSolution.html` in a web browser.
3. Observe the rendering and any differences in validation.

## Solution

Always use lowercase for HTML attribute values for consistency and validation purposes.  This ensures that your code will be interpreted correctly across all browsers and tools.