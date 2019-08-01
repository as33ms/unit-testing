# unit-testing
Various unit testing learning examples
# tasks
* [ ] Create a small PHP script that accepts a string as input and returns if its a palindrome or not. The output is returned in one of the output formats which the user sets during the GET request.
  * Data is accepted as GET parameter
  * Parameters of the script:
     * ```str```: the string which should be tested for palindrome
     * ```format```: the format of the result
  * Output formats:
     * JSON: ```{str: "the original string", is_palindrome: "false"}```
     * RAW: ```"the orginal string" is not a palindrome```
     * XML: Define your own xml syntax (see w3c for standards)
* [ ] Write unit tests using any one of the following
  * Python (py-unit)
  * Ruby (ruby-unit)
  * Php Unit (php-unit)
