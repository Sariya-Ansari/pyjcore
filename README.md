# pyjcore
pyjcore is a Python library designed to replicate key aspects of Java's collections framework and string handling.

## Project Overview
pyjcore is a Python library designed to replicate key aspects of Java's collections framework and string handling functionalities.
This project aims to provide Pythonic equivalents of Java's well-established data structures and string utilities, making it easier for developers familiar with Java to transition to Python.

### jcollections
The jcollections library mirrors Java's collection framework and allows java like methods.
It allows to operate on various data structures  like List, Map, Vector, Set, Queue etc.



### jstring
The jstring library is a Pythonic recreation of Java's String class, designed to support various string manipulations and utilities.
Key functionalities include:

String Initialization: Supports constructors for initializing strings from raw data, other string-like objects, and byte arrays.
String Operations:
Methods for substring extraction, character retrieval, and code point operations.
Utility methods like toLowerCase, toUpperCase, and trim.
Formatting and Conversion: Provides methods for formatting, comparing, and converting strings.
These features enhance string handling by offering common transformations and manipulations similar to Java's String class.

### Testing
To ensure correctness and reliability, the project includes:

API Usage Tests: Validate core functionalities and interactions of the collection classes, demonstrating expected behaviors through various operations.
Unit Tests: Specifically target the String class, covering a wide range of string operations to ensure conformance to Java's String class behavior.

### Conclusion
The jcollections and jstring libraries provide robust tools for Python developers who need Java-like collection and string handling capabilities. By mimicking Java’s well-known frameworks and utilities, these libraries offer a familiar interface for Java developers and extend Python’s capabilities in handling complex data structures and string operations.

## Installation

You can install the package using pip command:

```bash
pip install pyjcore
```

## Unit Test
Goto the project root directory & run the below command
Run Below Command: (change the name of unit test file)
```
python -m unittest tests.test_stringbuilder
```



