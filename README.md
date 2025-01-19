# Unhandled jsonDecode Exception in Dart Async Function

This repository demonstrates a common error in Dart asynchronous programming: neglecting to handle potential exceptions during JSON decoding.  The `bug.dart` file showcases the error, while `bugSolution.dart` provides a corrected version.

The issue arises when an API call returns invalid JSON, causing `jsonDecode` to throw a `FormatException`.  The initial code lacks proper exception handling, leading to program crashes. The solution adds comprehensive error handling to gracefully manage these scenarios.

## How to Run

1. Clone this repository.
2. Ensure you have Dart SDK installed.
3. Run the Dart files using the Dart command line or an IDE like VS Code.