# Guidelines

- No short variables like pass (password), e (event) or err (error)
- No double quotes unless you are using new line /n etc
- No ugly _ prefix for private methods, use methods outside of the class or object and bind them to context
- No _ in file names. We can use dash or camelCase but no _
- Class names are always getting styled as camel cased ClassNames all the time. A class is class it’s role doesn’t change it’s type. No exception.
- Always use strict checking === as long as it doesn’t meant to check all kinds of false etc.
- Nested folders are causes distraction, cost of time to find and understand. Also it’s easier to cause bugs related to paths. No more than 1 nested folder.
- For nesting things, nest the file names instead of Parent/category/child_component -> ParentCategoryChildComponent. Long but correct names are welcome.
- Editor have a ruler for limiting line ending, never breach it (For HTML as well).
- Commit often, push often after every feature. Even for typo fixing.
- Use documentation for methods
- Watch for spaces before brackets for things like functions, operators : if { , function { , for { etc, { Module }
- Use and IDE like WebStorm or plugin that makes spellchecking to your code
- Linter warnings shouldn’t be ignored
