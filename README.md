# CSS Specificity Gotcha: !important Override

This repository demonstrates a subtle but important CSS specificity issue related to the use of the `!important` flag.  The example highlights a case where a seemingly high-priority `!important` style declaration is unexpectedly overridden by a more specific selector.

The bug.css file contains the problematic CSS code. The bugSolution.css file offers a solution.  Understanding this can help avoid unexpected styling behaviors in complex CSS structures.