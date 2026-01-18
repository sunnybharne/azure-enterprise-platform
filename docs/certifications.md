# Certifications

- MS Learn: [https://learn.microsoft.com/en-us/](https://learn.microsoft.com/en-us/)
- Career Path: [https://learn.microsoft.com/en-us/training/career-paths/](https://learn.microsoft.com/en-us/training/career-paths/)

## Administrator

### AZ-900
Link: [https://learn.microsoft.com/en-us/training/career-paths/administrator](https://learn.microsoft.com/en-us/training/career-paths/administrator)

#### Describe cloud concepts (25-30%)

##### Describe cloud computing

#### Describe Azure architecture and services (35-40%)

#### Describe Azure management and governance

#### Test

## AI Engineer

## Developer
Link : https://learn.microsoft.com/en-us/plans/qpw7uqt4x85g0p?source=docs&ref=profile#learn-wwl-get-started-c-sharp-part-1

FreeCodeCamp c# Link : https://www.freecodecamp.org/learn/foundational-c-sharp-with-microsoft/

### Part 1 (Write your first c# code)
#### Basics
```c#
  Console.Write("Hello World");
  Console // Class
  . // Member Access Operator
  WriteLine // Method
  () // Method Invocation Operator
```
#### Print Commands
```c#
  Console.Write("Hello World"); // printf
  Console.WriteLine("Hello World"); // printf + /n
```
#### DataType
```c#
  // Integer
```

##### Character
```c#
char myChar = 'A';              // Single character, single quotes
char digit = '5';
char symbol = '@';
char newline = '\n';
char tab = '\t';
char unicode = '\u03A9';        // Greek capital letter Omega (Ω)
```

##### Numeric Types

**Integer Types:**
```c#
// Signed integers
sbyte mySbyte = -128;           // 8-bit, -128 to 127
short myShort = -32768;         // 16-bit, -32,768 to 32,767
int myInt = -2147483648;        // 32-bit, -2,147,483,648 to 2,147,483,647
long myLong = -9223372036854775808L;  // 64-bit, suffix L or l

// Unsigned integers
byte myByte = 255;              // 8-bit, 0 to 255
ushort myUshort = 65535;        // 16-bit, 0 to 65,535
uint myUint = 4294967295U;      // 32-bit, suffix U or u
ulong myUlong = 18446744073709551615UL;  // 64-bit, suffix UL or ul

// Literal examples
int decimalNum = 42;
int hexNum = 0x2A;              // Hexadecimal
int binaryNum = 0b101010;       // Binary (C# 7.0+)
```

**Floating-Point Types:**
```c#
float myFloat = 3.14F;          // 32-bit, suffix F or f
double myDouble = 3.14159;      // 64-bit, default for decimals
double myDouble2 = 3.14159D;    // Explicit suffix D or d
decimal myDecimal = 3.14159M;   // 128-bit, suffix M or m (for money/precision)
```

##### Boolean
```c#
bool isTrue = true;
bool isFalse = false;
bool defaultBool;  // Default value is false
```

##### String
```c#
string myString = "Hello";      // String, double quotes
string multiLine = @"Multi
Line
String";                        // Verbatim string (preserves newlines)
string interpolated = $"Hello {name}";  // String interpolation
```

##### DateTime
```c#
DateTime now = DateTime.Now;
DateTime specific = new DateTime(2024, 1, 15);
DateTime parsed = DateTime.Parse("2024-01-15");
DateOnly dateOnly = new DateOnly(2024, 1, 15);  // C# 10+
TimeOnly timeOnly = new TimeOnly(14, 30);       // C# 10+
```

##### Arrays
```c#
// Single-dimensional
int[] numbers = new int[5];
int[] numbers2 = {1, 2, 3, 4, 5};
int[] numbers3 = new int[] {1, 2, 3};

// Multi-dimensional
int[,] matrix = new int[3, 3];
int[,] matrix2 = {{1, 2}, {3, 4}};

// Jagged arrays
int[][] jagged = new int[3][];
jagged[0] = new int[] {1, 2, 3};
```

##### Collections
```c#
// List
List<int> numbers = new List<int>();
List<int> numbers2 = new List<int> {1, 2, 3};

// Dictionary
Dictionary<string, int> ages = new Dictionary<string, int>();
Dictionary<string, int> ages2 = new Dictionary<string, int>
{
    {"Alice", 25},
    {"Bob", 30}
};

// HashSet
HashSet<int> uniqueNumbers = new HashSet<int> {1, 2, 3};
```

##### Nullable Types
```c#
int? nullableInt = null;        // Can be null
int? nullableInt2 = 42;
bool? nullableBool = null;
DateTime? nullableDate = null;

// Or using Nullable<T>
Nullable<int> nullableInt3 = null;
```

##### var Keyword (Type Inference)
```c#
var number = 42;                // Compiler infers int
var name = "John";              // Compiler infers string
var isActive = true;            // Compiler infers bool
var list = new List<int>();     // Compiler infers List<int>
```

##### Default Values
```c#
// Value types have default values
int defaultInt;                 // 0
float defaultFloat;             // 0.0
bool defaultBool;               // false
char defaultChar;               // '\0'

// Reference types default to null
string defaultString;           // null
object defaultObject;           // null
```

##### Type Conversion
```c#
// Implicit conversion (safe, no data loss)
int i = 42;
long l = i;                     // int to long

// Explicit conversion (cast)
double d = 3.14;
int i2 = (int)d;                // 3 (truncates)

// Using Convert class
string str = "42";
int i3 = Convert.ToInt32(str);

// Using Parse methods
int i4 = int.Parse("42");
bool b = bool.Parse("true");

// Using TryParse (safe)
if (int.TryParse("42", out int result))
{
    // Use result
}
```


### Part 2 (Store and retrieve data using literal and variable values in C#)
### Part 3
### Part 4
### Part 5
### Part 6

## Identity and Access Administrator

## DevOps Engineer

## Security Engineer

## Data Analyst

## Solutions Architect

## Data Engineer

## Data Scientist

## Security Operation Analyst

## App Maker

## Business User

## Auditor
