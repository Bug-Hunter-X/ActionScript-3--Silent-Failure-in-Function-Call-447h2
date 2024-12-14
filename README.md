# ActionScript 3 Silent Function Failure

This repository demonstrates a common, yet subtle, error in ActionScript 3 where a function is defined but never actually executed, leading to unexpected silent failures.  The `bug.as` file shows the erroneous code, while `bugSolution.as` provides the corrected version.

The problem highlights the importance of ensuring that functions are correctly called within the appropriate execution context (like an event handler or the main application entry point).