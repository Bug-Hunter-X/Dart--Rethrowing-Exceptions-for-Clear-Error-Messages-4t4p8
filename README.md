# Dart: Rethrowing Exceptions for Clear Error Messages

This repository demonstrates a common error handling issue in Dart and provides a solution for better error reporting.

The `bug.dart` file showcases an example where an exception is caught, but the specific error message is lost without `rethrow`.  This leads to less informative error messages when debugging.

The `bugSolution.dart` file illustrates the correct approach: using `rethrow` to maintain the original exception details, enabling more precise debugging and error handling.

This example showcases the importance of thoughtfully handling and propagating exceptions in Dart applications for improved developer experience and debugging.