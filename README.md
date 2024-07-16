# String Comparison Example

This C# program demonstrates various string comparison techniques using the `StringCompare` class.

## Overview

The `StringCompare` class compares and analyzes four strings:

- `string1`: "hello"
- `string2`: "good bye"
- `string3`: "Happy Birthday"
- `string4`: "happy birthday"

### Comparison Techniques

1. **Equality Using `Equals` Method:**
   - Checks if `string1` equals "hello" using `Equals` method.

2. **Equality Using `==` Operator:**
   - Checks if `string1` equals "hello" using `==` operator.

3. **Case-Sensitive Comparison:**
   - Compares `string3` ("Happy Birthday") and `string4` ("happy birthday") using `string.Equals` method to demonstrate case sensitivity.

4. **Comparison Using `CompareTo` Method:**
   - Compares pairs of strings (`string1` with `string2`, `string2` with `string1`, `string1` with itself, `string3` with `string4`, and `string4` with `string3`) using `CompareTo` method to determine their order.

## How to Use

1. **Compile and Run the Program:**
   - Ensure you have a C# compiler installed.
   - Compile the program using `csc StringCompare.cs`.
   - Run the program with `StringCompare.exe`.

2. **Output:**
   - The program will output the initial values of the strings.
   - It will then show the results of various comparison operations as described above.

### Example Output

