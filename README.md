# ASSESSMENT-S7

Here is the debugged code for the weather website. I've addressed syntax errors, runtime errors, and logic errors to ensure a smooth user experience. The corrected code now accurately handles city input, retrieves the current temperature, and seamlessly integrates quirky messages based on the weather conditions.

BELOW YOU WILL FIND THE TRANSCRIPT OF WHAT IVE CHANGED TO DEBUG. 

Error in Line 3:
A syntax error occurred, where an apostrophe was used instead of a quotation mark at the end of the id selector. The error was highlighted in Visual Studio Code.
Error in Line 4:
A runtime error due to a misspelt function name. The error was identified later during debugging using the console in the Chrome inspection tool when the error became visible.
Error in Line 17:
A fetching error, resulting in incorrect data retrieval. NaN was displayed when searching for temperature. To locate the correct key, I utilised 'console.log(data)' during debugging.
Error in Line 18:
The displayed temperature showed multiple decimals instead of a whole/rounded number. Resolved by adding 'Math.ceil(temp)' to round the number appropriately.
Error in Line 19:
A syntax error was identified due to incorrect quotation marks. Rectified by using backticks in ' ${temp}°C '.
Error in Line 29:
A logical error was present, and the order was adjusted to be mirrored.
Error in Line 34:
A logic error occurred due to a missing equals symbol, preventing the correct message from corresponding with the temperature of the city.
Error in Line 39:
A syntax error was detected, with missing parenthesis. Addressed by adding parenthesis around 'e' after 'function'.
Error in Line 40:
A runtime error surfaced due to a missing element. Prevented the page from reloading by adding 'e.' onto 'preventDefault()' to obtain the desired result.
