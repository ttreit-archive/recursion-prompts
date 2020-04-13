# Specification
<!-- ## IOCE -->
**Input**: number
**Output**: factorial of number
**Constraints**: use recursion, no extra parameters
**Edge Cases**: negative numbers, zero

# Justification
<!-- ## Purpose of Calling this Function -->
To get the factorial of the given number

# Explanation
<!-- ## Clearly state relationship between Inputs and Outputs in Plain English -->
To get the factorial we will multiply the number by all positive integers less than or equal to the given number.
Example: num = 5;  5x4x3x2x1

# Visualization
<!-- ## Whiteboard - draw plan that another engineer could understand. Use pictures and labels maybe sample data -->

<!-- select and copy image to clipboard -->
<!-- Use cmd + alt + v to paste (vsc paste image extn) -->
![](2020-04-12-18-57-23.png)

# Approximation
<!-- ## Pseudocode -->
<!-- Complete, without ambiguity, high level as possible, indented to show subordinate steps, translateable to one real line of code -->
//function (num)
// if num is greater than 0
// result = num * function (num -1)
//return result

# Verification
<!-- Use sample data to walk through pseudocode
Write one sanity test -->
function(3) // expect 6

# Implementation
Go Code!
<!-- Code! -->
