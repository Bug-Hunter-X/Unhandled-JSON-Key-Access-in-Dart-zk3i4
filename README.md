# Unhandled JSON Key Access in Dart

This repository demonstrates a common error in Dart when working with JSON responses: attempting to access a key that doesn't exist.  The `bug.dart` file shows the problematic code, while `bugSolution.dart` provides a corrected version.

The issue arises when parsing JSON and directly accessing keys without checking for their presence.  This can result in runtime exceptions, disrupting the application's flow. The solution demonstrates robust error handling and key existence verification.