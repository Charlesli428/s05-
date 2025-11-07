Code Smells and Fixes

Duplicate logic → Moved repeated update code into a single updateCounterUI() function.

Mixed responsibilities → Split UI creation into createCounterUI() and kept event setup in setup().

Unclear variable names → Renamed short variables (c, a, b, etc.) to clear names like counter, incrementButton, counterElement.

Magic literals → Used constants for button IDs and header text.

Global state → Kept counter in one place and updated only through event handlers.
