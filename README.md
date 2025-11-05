# Readable Rust Code

I recently came across a superb ebook called **"100 Techniques for Writing Readable Rust Code"** by Kanro Tomoya. This is an invaluable guide for any Rust developer aiming to write cleaner and more idiomatic code.

The original versions I found were in EPUB and a converted PDF, which can be harder to read and navigate. Additionally, the original formats lack code syntax highlighting, making the Rust examples less clear. To improve the experience, I have converted the ebook into Markdown. Furthermore, I've enhanced it by adding intuitive navigation buttons (Previous, Home, Next) at the end of every chapter for a smoother reading flow.

Heartfelt thanks to Kanro Tomoya for creating this excellent resource and sharing it with the Rust community.

## Table of Contents

| Number | Title |
| ------ | ----- |
| 1 | [Use pattern matching with match for clear and concise control flow](contents/1.md) |
| 2 | [Leverage Option and Result types for safe and explicit error handling](contents/2.md) |
| 3 | [Utilize iter, map, and filter for functional-style data processing](contents/3.md) |
| 4 | [Employ enum to represent a type that can be one of several variants](contents/4.md) |
| 5 | [Use trait to define shared behavior across different types](contents/5.md) |
| 6 | [Name variables and functions descriptively to convey their purpose](contents/6.md) |
| 7 | [Use snake_case for variable and function names for consistency](contents/7.md) |
| 8 | [Prefix boolean variables with is_, has_, or can_ to indicate their nature](contents/8.md) |
| 9 | [Use const and static for constants to make their immutability clear](contents/9.md) |
| 10 | [Name modules and files to reflect their contents and purpose](contents/10.md) |
| 11 | [Avoid abbreviations that are not universally understood](contents/11.md) |
| 12 | [Use full words instead of single letters for variable names](contents/12.md) |
| 13 | [Avoid using similar names for different variables to prevent confusion](contents/13.md) |
| 14 | [Ensure function names clearly describe their actions or results](contents/14.md) |
| 15 | [Use consistent naming conventions throughout the codebase](contents/15.md) |
| 16 | [Use impl blocks to group related methods for a type](contents/16.md) |
| 17 | [Leverage From and Into traits for type conversions](contents/17.md) |
| 18 | [Use Cow (Clone on Write) for efficient handling of borrowed and owned data](contents/18.md) |
| 19 | [Utilize Rc and Arc for reference counting and shared ownership](contents/19.md) |
| 20 | [Use RefCell and Mutex for interior mutability and thread safety](contents/20.md) |
| 21 | [Comment on the purpose of complex algorithms or data structures](contents/21.md) |
| 22 | [Explain the reasoning behind non-obvious design decisions](contents/22.md) |
| 23 | [Document the expected input and output of functions](contents/23.md) |
| 24 | [Comment on the usage of unsafe code and its safety guarantees](contents/24.md) |
| 25 | [Use doc comments (///) to generate documentation for public APIs](contents/25.md) |
| 26 | [Keep comments up-to-date with code changes](contents/26.md) |
| 27 | [Avoid redundant comments that restate the obvious](contents/27.md) |
| 28 | [Use comments to explain why, not what, the code is doing](contents/28.md) |
| 29 | [Be concise and to the point in your comments](contents/29.md) |
| 30 | [Use TODO comments to indicate areas for future improvement](contents/30.md) |
| 31 | [Use ? operator for concise error propagation](contents/31.md) |
| 32 | [Leverage async and await for asynchronous programming](contents/32.md) |
| 33 | [Use Box for heap allocation and dynamic dispatch](contents/33.md) |
| 34 | [Utilize Vec for dynamic arrays and HashMap for key-value storage](contents/34.md) |
| 35 | [Use slice and str for efficient string and array handling](contents/35.md) |
| 36 | [Format code consistently using rustfmt](contents/36.md) |
| 37 | [Organize code into modules and submodules logically](contents/37.md) |
| 38 | [Use whitespace and indentation to enhance readability](contents/38.md) |
| 39 | [Group related code together and separate different sections with blank lines](contents/39.md) |
| 40 | [Avoid deeply nested code by refactoring into smaller functions](contents/40.md) |
| 41 | [Use if let and while let for concise conditional checks](contents/41.md) |
| 42 | [Prefer for loops over while loops for iteration](contents/42.md) |
| 43 | [Use break and continue judiciously to control loop flow](contents/43.md) |
| 44 | [Avoid complex nested match statements by refactoring into functions](contents/44.md) |
| 45 | [Use return early to handle error cases and reduce nesting](contents/45.md) |
| 46 | [Use match guards to add conditions to pattern matches](contents/46.md) |
| 47 | [Leverage Result's combinators like map and and_then](contents/47.md) |
| 48 | [Use unwrap_or and unwrap_or_else for default values](contents/48.md) |
| 49 | [Utilize Option's combinators like map and and_then](contents/49.md) |
| 50 | [Use Result and Option for error handling and optional values](contents/50.md) |
| 51 | [Leverage Cow for efficient handling of borrowed and owned data](contents/51.md) |
| 52 | [Use Rc and Arc for reference counting and shared ownership](contents/52.md) |
| 53 | [Utilize RefCell and Mutex for interior mutability and thread safety](contents/53.md) |
| 54 | [Use Box for heap allocation and dynamic dispatch](contents/54.md) |
| 55 | [Leverage async and await for asynchronous programming](contents/55.md) |
| 56 | [Use descriptive names for variables to indicate their purpose](contents/56.md) |
| 57 | [Avoid Single-Letter Variable Names](contents/57.md) |
| 58 | [Use 'let' for Declarations, 'mut' Only When Necessary](contents/58.md) |
| 59 | [Group Related Variables](contents/59.md) |
| 60 | [Use Constants for Unchanging Values](contents/60.md) |
| 61 | [Break down complex functions into smaller, single-purpose functions](contents/61.md) |
| 62 | [Use helper functions to encapsulate repetitive code](contents/62.md) |
| 63 | [Avoid side effects in functions](contents/63.md) |
| 64 | [Use clear and descriptive function names](contents/64.md) |
| 65 | [Limit the number of parameters a function takes](contents/65.md) |
| 66 | [Use impl blocks to group related methods for a type](contents/66.md) |
| 67 | [Leverage From and Into traits for type conversions](contents/67.md) |
| 68 | [Use Cow (Clone on Write) for efficient handling of borrowed and owned data](contents/68.md) |
| 69 | [Utilize Rc and Arc for reference counting and shared ownership](contents/69.md) |
| 70 | [Use RefCell and Mutex for interior mutability and thread safety](contents/70.md) |
| 71 | [Break Down Large Expressions](contents/71.md) |
| 72 | [Use Intermediate Variables](contents/72.md) |
| 73 | [Refactor complex expressions into helper functions](contents/73.md) |
| 74 | [Use parentheses to make the order of operations explicit](contents/74.md) |
| 75 | [Avoid chaining too many method calls in a single line](contents/75.md) |
| 76 | [Identify and extract unrelated sub-problems into separate functions](contents/76.md) |
| 77 | [Use helper functions to encapsulate distinct tasks](contents/77.md) |
| 78 | [Modularize code to separate concerns and improve readability](contents/78.md) |
| 79 | [Use traits to define shared behavior and reduce code duplication](contents/79.md) |
| 80 | [Refactor large functions into smaller, more manageable pieces](contents/80.md) |
| 81 | [Use ? operator for concise error propagation](contents/81.md) |
| 82 | [Leverage async and await for asynchronous programming](contents/82.md) |
| 83 | [Use Box for heap allocation and dynamic dispatch](contents/83.md) |
| 84 | [Utilize Vec for dynamic arrays and HashMap for key-value storage](contents/84.md) |
| 85 | [Use slice and str for efficient string and array handling](contents/85.md) |
| 86 | [Choose Vec for dynamic arrays when the size is unknown at compile time](contents/86.md) |
| 87 | [Use HashMap for key-value pairs when fast lookup is needed](contents/87.md) |
| 88 | [Leverage BTreeMap for ordered key-value storage](contents/88.md) |
| 89 | [Use Option and Result for optional and error-prone values](contents/89.md) |
| 90 | [Choose Rc and Arc for shared ownership and reference counting](contents/90.md) |
| 91 | [Use Result for Error Handling](contents/91.md) |
| 92 | [Leverage unwrap_or and unwrap_or_else for Default Values](contents/92.md) |
| 93 | [Use expect with meaningful error messages for debugging](contents/93.md) |
| 94 | [Handle errors at the appropriate level of abstraction](contents/94.md) |
| 95 | [Use thiserror or anyhow crates for custom error types and handling](contents/95.md) |
| 96 | [Write generic functions to handle multiple types](contents/96.md) |
| 97 | [Use traits to define shared behavior and enable polymorphism](contents/97.md) |
| 98 | [Leverage impl Trait for concise and flexible function signatures](contents/98.md) |
| 99 | [Use macro_rules! to create reusable macros](contents/99.md) |
| 100 | [Refactor common patterns into reusable functions or modules](contents/100.md) |
| 101 | [Use crate and pub keywords to control visibility and reuse](contents/101.md) |
| 102 | [Leverage Cargo workspaces to manage multiple related packages](contents/102.md) |
