Download Link: https://assignmentchef.com/product/solved-function-pointers
<br>
<p class="ui header product-top-header" title="Function pointers Solution">1.Function pointersWrite a function squareRoot that uses the Newton’s method of approximate calcu-lation of the square root of a number x. The Newton’s method guesses the square root in

x

iterations. The first guess is ——. In each iteration the guess is improved using

2

x

guess + ———–

guess

—————————-    as the next guess.

2

Your main program should prompt the user for the value to find the square root of (x) and how close the final guess should be to the previous guess (for example, 0.001), and pass these values to the squareRoot function. As a third argument of the function squareRoot pass an error processing function, to be called if the other arguments do not pass validation. For example the error processing function can set the wrong arguments to some default values, or ask the user for new values, or do some other appropriate action. Test squareRoot with at least two error processing functions.