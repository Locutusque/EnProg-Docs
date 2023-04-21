Welcome to EnProg Documentation!
===============================

EnProg is a programming language designed to be simple, readable, and powerful. With EnProg, you can quickly create powerful programs without worrying about complex syntax or difficult programming concepts.

Python Variant
--------------

To get started with the Python Variant, you can import it at the top of your script using `"from ENPROG.enprog import EnProg"`.

To keep your code clean, it is suggested that you import it as `"EP"` or `"ep"`.

To run your EnProg code, you can use the `run_program(file_path)` function, where the `file_path` parameter is a directory for the file that you want to run.

You can use the `check_syntax(program)` function to check the syntax of given code. The `program` parameter is a string of the code that you want to check (it is not a directory). This returns a list of errors found in the given code. Keep in mind that this function may be unstable because it has not been tested much.

The `translate_program(program)` function, where the `program` parameter is a string that contains code, translates the given code into Python. This returns a string, which is the Python equivalent from the EnProg code.

You can import all of your EnProg code into a Python script using the `importPackage(file_path, class_name)` function, where the `file_path` is the path of the file that you want to import, and `class_name` is the name of class that you want to import. This function returns an instance of the imported class.

The deprecated function `getPackage` should not, but can be used to import packages from EnProg. This function has one parameter which is a string for the directory of the file that you wish to import. This returns the directory for a compiled file that can then be imported.

You can also use the command prompt to run EnProg code. Usage: `enprog [run|import|check|translate] [parameters for the corresponding function]`.

Java Variant (untested could be unstable)
------------------------------------------

To get started with the Java Variant, you can set the GitHub repository of this as a dependency in your `pom.xml`, or download it manually from GitHub.

The Java Variant has the same functions and parameters as the Python Variant. The only difference is that it cannot be run immediately like the Python Variant because Java is a compiled programming language.

The functions are the same, but the names are changed to follow coding conventions. The renamed functions are: `translateProgram`, `runProgram`, `checkSyntax`, `getPackage`, and `importPackage`. These functions, although renamed, have the same parameters and return values as the Python Variant.
