# Specification
<!-- ## IOCE -->
**Input**: array of numbers

**Output**: sum of the numbers

**Constraints**: use recursion, no adding parameters

**Edge Cases**: empty array

# Justification
<!-- ## Purpose of Calling this Function -->
Add up the numbers inside of an array

# Explanation
<!-- ## Clearly state relationship between Inputs and Outputs in Plain English -->
We will get an array of numbers that we must add together.

# Visualization
<!-- ## Whiteboard - draw plan that another engineer could understand. Use pictures and labels maybe sample data -->

<!-- select and copy image to clipboard -->
<!-- Use cmd + alt + v to paste (vsc paste image extn) -->
![](2020-04-12-19-08-53.png)

# Approximation
<!-- ## Pseudocode -->
<!-- Complete, without ambiguity, high level as possible, indented to show subordinate steps, translateable to one real line of code -->
// base case = empty array return 0

// return first array element and remove from array

// add first element to function(array)

# Verification
<!-- Use sample data to walk through pseudocode
Write one sanity test -->
function([1, 2, 3]) = 6

function ([2]) = 2

function ([]) = 0


# Implementation
<!-- Code! -->
