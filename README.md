EASY

"Convert Celsius to Fahrenheit" 

// fahrenheit variable is equal to the formula that lets us convert to fahrenheit.
// we return the variable ... so 30 * 9/5 + 32 ====> 86 F.

function convertCtoF(celsius) {
  let fahrenheit = celsius * (9/5) + 32;
  return fahrenheit;
}

convertCtoF(30);
-----------------------------------------------------------------------------------------------
EASY

"Reversing A String"

//we are using the split reverse and join methods in order to achieve this solution;
//we .split("") the string into its own little string ("h" "e" "l" "l" "o");
// we reverse the strings with .reverse("") which leaves us with ("o" "l" "l" "e" "h");
//we then use the .join("") to join the string into one big string leaving us with ("olleh")



function reverseString(str) {
  return str.split("").reverse("").join("");
}

reverseString("hello");

---------------------------------------------------------------------------------------------
EASY 







