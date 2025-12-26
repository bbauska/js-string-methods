<h1>js-string-methods</h1>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2>JavaScript String Methods</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>JavaScript provides a variety of built-in methods to work with strings — allowing you to extract, 
modify, search, and format text with ease. Below are some of the most commonly used core string 
methods:</p>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>slice()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>slice()</b> extracts a part of the string based on the given stating-index and ending-index 
and returns a new string.</p>

<pre>
// Define a string variable 
let A = 'Geeks for Geeks';

// Use the slice() method to extract a substring
let b = A.slice(0, 5);
let c = A.slice(6, 9);
let d = A.slice(10);

// Output the value of variable
console.log(b);
console.log(c);
console.log(d);
</pre>

<h4>Output</h4>

<blockquote>
Geeks<br>
for<br>
Geeks
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>substring()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>substring()</b> returns the part of the given string from the start index to the end index. 
Indexing starts from zero (0).</p>

<pre>
// Define a string variable
let str = "Mind, Power, Soul";
​
// Use the substring() method to extract a substring 
let part = str.substring(6, 11);
​
// Output the value of variable
console.log(part);
</pre>

<h4>Output</h4>

<blockquote>
Power
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>substr()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>substr()</b> This method returns the specified number of characters from the specified index 
from the given string. It extracts a part of the original string.</p>

<pre>
// Define a string variable 'str'
let str = "Mind, Power, Soul";
​
// Use the substr() method to extract a substring f
let part = str.substr(6, 5);
​
// Output the value of variable
console.log(part);
</pre>

<h4>Output</h4>

<blockquote>
Power
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>replace()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>replace()</b> replaces a part of the given string with another string or a regular expression. 
The original string will remain unchanged.</p>

<pre>
// Define a string variable 'str' 
let str = "Mind, Power, Soul";
​
// Use the replace() method to replace the substring
let part = str.replace("Power", "Space");
​
// Output the resulting string after replacement
console.log(part);
</pre>

<h4>Output</h4>

<blockquote>
Mind, Space, Soul
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>replaceAll()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>replaceAll()</b> returns a new string after replacing all the matches of a string with a 
specified string or a regular expression. The original string is left unchanged after this operation.</p>

<pre>
// Define a string variable 'str'
let str = "Mind, Power, Power, Soul";
​
// Use the replaceAll() method to replace all occurrences
//of "Power" with "Space" in the string 'str'
let part = str.replaceAll("Power", "Space");
​
// Output the resulting string after replacement
console.log(part);
</pre>

<h4>Output</h4>

<blockquote>
Mind, Space, Space, Soul
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>toUpperCase()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>toUpperCase()</b> converts all the characters present in the String to upper case and returns 
a new String with all characters in upper case. This method accepts single parameter stringVariable 
string that you want to convert in upper case.</p>

<pre>
// Define a string variable
let gfg = 'GFG ';
​
// Define another string variable 
let geeks = 'stands-for-GeeksforGeeks';
​
// Convert the string 'geeks' to uppercase using the toUpperCase() method
console.log(geeks.toUpperCase());
</pre>

<h4>Output</h4>

<blockquote>
STANDS-FOR-GEEKSFORGEEKS
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>toLowerCase()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>toLowerCase()</b> converts all the characters present in the so lowercase and returns a new 
string with all the characters in lowercase.</p>

<pre>
// Define a string variable
let gfg = 'GFG ';
​
// Define a string variable 
let geeks = 'stands-for-GeeksforGeeks';
​
// Convert the string 'geeks' to lowercase using the toLowerCase() method
console.log(geeks.toLowerCase());
</pre>

<h4>Output</h4>

<blockquote>
stands-for-geeksforgeeks
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>toLowerCase()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>toLowerCase()</b> converts all the characters present in the so lowercase and returns a new 
string with all the characters in lowercase.</p>

<pre>
// Define a string variable
let gfg = 'GFG ';
​
// Define a string variable 
let geeks = 'stands-for-GeeksforGeeks';
​
// Convert the string 'geeks' to lowercase using the toLowerCase() method
console.log(geeks.toLowerCase());
</pre>

<h4>Output</h4>

<blockquote>
stands-for-geeksforgeeks
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>concat()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>concat()</b> combines the text of two strings and returns a new combined or joined string. 
To concatenate two strings, we use the concat() method on one object of string and send another 
object of string as a parameter. This method accepts one argument. The variable contains text in 
ouble quotes or single quotes.</p>

<pre>
let gfg = 'GFG ';
let geeks = 'stands for GeeksforGeeks';
​
// Accessing concat method on an object
// of String passing another object 
// as a parameter
console.log(gfg.concat(geeks));
</pre>
<h4>Output</h4>

<blockquote>
GFG stands for GeeksforGeeks
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>trim()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>trim()</b> is used to remove either white spaces from the given string. This method returns 
a new string with removed white spaces. This method is called on a String object. This method 
doesn't accept any parameter.</p>

<pre>
let gfg = 'GFG    ';
let geeks = 'stands-for-GeeksforGeeks';
​
// Storing new object of string
// with removed white spaces
let newGfg = gfg.trim();
​
// Old length
console.log(gfg.length);
​
// New length
console.log(newGfg.length)
</pre>

<h4>Output</h4>

<blockquote>
7<br>
3
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>trimStart()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>trimStart()</b> removes whitespace from the beginning of a string. The value of the string 
is not modified in any manner, including any whitespace present after the string.</p>

<pre>
// Define a string variable 
let str = "  Soul";
​
// Output the original value of the string 
console.log(str);
​
// Use the trimStart() method to remove leading whitespace from the string 'str'
let part = str.trimStart();
​
// Output the resulting string after removing leading whitespace
console.log(part);
</pre>

<h4>Output</h4>

<blockquote>
  Soul<br>
Soul
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>trimEnd()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>trimEnd()</b> removes white space from the end of a string. The value of the string is not 
modified in any manner, including any white-space present before the string.</p>

<pre>
// Define a string variable 
let str = "Soul  ";
​
// Output the original value of the string 'str'
console.log(str);
​
// Use the trimEnd() method to remove trailing whitespace from the string 'str'
let part = str.trimEnd();
​
// Output the resulting string after removing trailing whitespace
console.log(part);
</pre>

<h4>Output</h4>

<blockquote>
Soul<br>
Soul
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>padStart()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>padStart()</b> pad a string with another string until it reaches the given length. The padding 
is applied from the left end of the string.</p>

<pre>
// Define a string variable 
let stone = "Soul";
​
// Use the padStart() method to add padding characters "Mind "
//to the beginning of the string 'stone' 
stone = stone.padStart(9, "Mind ");
​
// Output the resulting string after padding
console.log(stone);
</pre>

<h4>Output</h4>

<blockquote>
Mind Soul
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>padEnd()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>padEnd()</b> pad a string with another string until it reaches the given length. The padding 
is applied from the right end of the string.</p>

<pre>
// Define a string variable 
let stone = "Soul";
​
// Use the padEnd() method to add padding characters
//" Power" to the end of the string 'stone' 
stone = stone.padEnd(10, " Power");
​
// Output the resulting string after padding
console.log(stone);
</pre>

<h4>Output</h4>

<blockquote>
Soul Power
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>charAt()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>charAt()</b> returns the character at the specified index. String in JavaScript has zero-
based indexing.</p>

<pre>
let gfg = 'GeeksforGeeks';
let geeks = 'GfG is the best platform to learn and\n'+
'experience Computer Science.';
​
// Print the string as it is
console.log(gfg); 
​
console.log(geeks); 
​
// As string index starts from zero
// It will return first character of string
console.log(gfg.charAt(0)); 
​
console.log(geeks.charAt(5));
</pre>

<h4>Output</h4>

<blockquote>
GeeksforGeeks<br>
GfG is the best platform to learn and<br>
experience Computer Science.<br>
G<br>
s
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>charCodeAt()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>charCodeAt()</b> returns a number that represents the Unicode value of the character at the 
specified index. This method accepts one argument.</p>

<pre>
let gfg = 'GeeksforGeeks';
let geeks = 'GfG is the best platform\n\
to learn and experience\n\
Computer Science.';
​
// Return a number indicating Unicode
// value of character at index 0 ('G')
console.log(gfg.charCodeAt(0));
console.log(geeks.charCodeAt(5));
</pre>

<h4>Output</h4>

<blockquote>
71<br>
115
</blockquote>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>split()</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p><b>split()</b> splits the string into an array of sub-strings. This method returns an array. 
This method accepts a single parameter character on which you want to split the string.</p>

<pre>
let gfg = 'GFG '
let geeks = 'stands-for-GeeksforGeeks'
​
// Split string on '-'. 
console.log(geeks.split('-'))
</pre>

<h4>Output</h4>

<blockqote>
&lbrack; 'stands', 'for', 'GeeksforGeeks' &rbrack;
</blockquote>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h3>More JS String Methods</h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p>Below is the JavaScript string functions list:</p>

<table style="width:75%; border:1px solid; background-color:#f3ffa9; text-align:center;">
  <caption>More JavaSCript String Methods</caption>
  <tr>
    <th><b>Instance Methods</b></th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-at-method/">at()</a></td>
    <td>Find the character at the specified index.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-anchor-method/">anchor()</a></td>
    <td>Creates an anchor element that is used as a hypertext target.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-charat-method/">charAt()</a></td>
    <td>Returns that character at the given index of the string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-charcodeat-method/">charCodeAt()</a></td>
    <td>Returns a Unicode character set code unit of the character present at the index in the string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-codepointat-method/">codePointAt()</a></td>
    <td>Return a non-negative integer value i.e, the code point value of the specified element.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-concat-method/">concat()</a></td>
    <td>Join two or more strings together in JavaScript.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-endswith-method/">endsWith()</a></td>
    <td>Whether the given string ends with the characters of the specified string or not.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-includes-method/">includes()</a></td>
    <td>Returns true if the string contains the characters, otherwise, it returns false.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-indexof-method/">indexOf()</a></td>
    <td>Finds the index of the first occurrence of the argument string in the given string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-lastindexof-method/">lastIndexOf()</a></td>
    <td>Finds the index of the last occurrence of the argument string in the given string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-localecompare-method/">localeCompare()</a></td>
    <td>Compare any two elements and returns a positive number.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-match-method/">match()</a></td>
    <td>Search a string for a match against any regular expression.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-matchall-method/">matchAll()</a></td>
    <td>Return all the iterators matching the reference string against a regular expression.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-normalize-method/">normalize()</td>
    <td>Return a Unicode normalization form of a given input string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-padend-method/">padEnd()</a></td>
    <td>Pad a string with another string until it reaches the given length from rightend.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-padstart-method/">padStart()</a></td>
    <td>Pad a string with another string until it reaches the given length from leftend.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-repeat-method/">repeat()</a></td>
    <td>Build a new string containing a specified number of copies of the string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-replace-method/">replace()</a></td>
    <td>Replace a part of the given string with some another string or a regular expression.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-replaceall-method/">replaceAll()</a></td>
    <td>Returns a new string after replacing all the matches of a string with a specified string/regex.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-search-method/">search()</td>
    <td>Search for a match in between regular expressions and a given string object.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-slice-method/">slice()</a></td>
    <td>Return a part or slice of the given input string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-split-method/">split()</a></td>
    <td>Separate given string into substrings using a specified separator provided in the argument.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-startswith-method/">startsWith()</a></td>
    <td>Check whether the given string starts with the characters of the specified string or not.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-substr-method/">substr()</a></td>
    <td>Returns the specified number of characters from the specified index from the given string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-substring-method/">substring()</a></td>
    <td>Return the part of the given string from the start index to the end index.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-tolowercase-method/">toLowerCase()</a></td>
    <td>Converts the entire string to lowercase.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-tolocalelowercase-method/">toLocaleLowerCase()</a></td>
    <td>Returns the calling string value converted to a lowercase letter.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-tolocaleuppercase-method/">toLocaleUpperCase()</a></td>
    <td>Returns the calling string value converted to a uppercase letter.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-touppercase-method/">toUpperCase()</a></td>
    <td>Converts the entire string to uppercase.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-tostring-method/">toString()</a></td>
    <td>Return the given string itself.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-trim-method/">trim()</a></td>
    <td>Remove the white spaces from both ends of the given string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-trimend-and-trimright-method/">
      trimEnd()</a></td>
    <td>Remove white space from the end of a string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-trimstart-and-trimleft-method/">
      trimStart()</a></td>
    <td>Remove white space from the start of a string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-valueof-method/">valueOf()</a></td>
    <td>Return the value of the given string.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-iterator-method/">
      string&lbrack;Symbol.iterator&rbrack;()</a></td>
    <td>This method is used to make String iterable. &lbrack;@@iterator&rbrack;() returns an iterator 
      object which iterates over all code points of the String.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-fromcharcode-method/">
      fromCharCode(n1, n2, ..., nX)</a></td>
    <td>This method is used to create a string from the given sequence of UTF-16 code units. This 
      method returns a string, not a string object.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-fromcodepoint-method/">
      fromCodePoint(a1, a2, a3, ....)</a></td>
    <td>This method in JavaScript that is used to return a string or an element for the given 
    sequence of code point values (ASCII value).</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-iswellformed-method/">isWellFormed()</a></td>
    <td>This method is used to check if the string contains a lone surrogate or not.</td>
  </tr>
  <tr>
    <td><a href="https://www.geeksforgeeks.org/javascript/javascript-string-raw-method/">String.raw(str, ...sub)</a></td>
    <td>This is a static method that is used to get the raw string form of template literals. These 
    strings do not process escape characters.</td>
  </tr>
  <tr>
    <td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toWellFormed">
      toWellFormed()</a></td>
    <td>This method is used to return where all lone surrogates of this string are replaced with the 
      Unicode replacement character.</td>
</table>



