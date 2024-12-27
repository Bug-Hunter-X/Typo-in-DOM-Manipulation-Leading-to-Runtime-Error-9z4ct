# Uncommon HTML Error: Typo in DOM Manipulation

This repository demonstrates a subtle but common error in JavaScript when working with the Document Object Model (DOM).  The error arises from a simple typo in the function used to access an HTML element.

The `bug.html` file contains the erroneous code, while `bugSolution.html` provides the corrected version.

**The Bug:**
The primary issue is the incorrect use of `document.getElementByIdx()` instead of the correct `document.getElementById()`.  This typo leads to a runtime error and prevents the intended modification of the HTML element.

**The Solution:**
The solution simply corrects the typo, ensuring the correct function is used to obtain the reference to the HTML element. 

This example highlights the importance of careful coding practices and thorough testing to prevent subtle errors from affecting the functionality of a web page.