# Program-6-of-the-C-

# Demonstration of Various Built-in Functions in VB.NET

## Aim
To demonstrate various built-in functions in VB.NET with suitable examples.

## Introduction
VB.NET provides built-in functions to perform mathematical calculations, manipulate strings, handle dates and times, and convert data types.

## 1. Mathematical Functions
- `Math.Abs()` – Returns the absolute value.
- `Math.Sqrt()` – Returns the square root.
- `Math.Pow()` – Calculates the power of a number.
- `Math.Round()` – Rounds a number.

Example:
```vbnet
Console.WriteLine(Math.Abs(-10))
Console.WriteLine(Math.Sqrt(25))
Console.WriteLine(Math.Pow(2, 3))
Console.WriteLine(Math.Round(12.56))
```

Output:
```text
10
5
8
13
```

## 2. String Functions
- `Len()` – Returns the length of a string.
- `UCase()` – Converts text to uppercase.
- `LCase()` – Converts text to lowercase.
- `Trim()` – Removes leading and trailing spaces.
- `Replace()` – Replaces specified text.

Example:
```vbnet
Console.WriteLine(Len("Pallavi"))
Console.WriteLine(UCase("hello"))
Console.WriteLine(LCase("WELCOME"))
Console.WriteLine(Trim("  VB.NET  "))
Console.WriteLine(Replace("Hello World", "World", "VB.NET"))
```

Output:
```text
7
HELLO
welcome
VB.NET
Hello VB.NET
```

## 3. Date and Time Functions
- `Date.Now` – Returns the current date and time.
- `Date.Today` – Returns the current date.
- `DateAdd()` – Adds a time interval to a date.
- `DateDiff()` – Calculates the difference between dates.

Example:
```vbnet
Console.WriteLine(Date.Now)
Console.WriteLine(Date.Today)
Console.WriteLine(DateAdd("d", 7, Date.Today))
Console.WriteLine(DateDiff("d", #10/01/2026#, #10/13/2026#))
```

## 4. Type Conversion Functions
- `CInt()` – Converts a value to an integer.
- `CDbl()` – Converts a value to a double.
- `CStr()` – Converts a value to a string.
- `CDate()` – Converts a value to a date.

Example:
```vbnet
Console.WriteLine(CInt("25"))
Console.WriteLine(CDbl("12.5"))
Console.WriteLine(CStr(100))
Console.WriteLine(CDate("10/13/2026"))
```

Output:
```text
25
12.5
100
10/13/2026
```

## 5. Other Built-in Functions
- `IsNumeric()` – Checks whether a value is numeric.
- `Val()` – Converts the beginning of a string to a number.
- `IIf()` – Returns one of two values based on a condition.

Example:
```vbnet
Console.WriteLine(IsNumeric("123"))
Console.WriteLine(Val("123ABC"))
Console.WriteLine(IIf(10 > 5, "True", "False"))
```

Output:
```text
True
123
True
```

## Conclusion
Thus, various built-in functions in VB.NET were demonstrated successfully. These functions simplify mathematical operations, string manipulation, date and time handling, and data type conversion.
