# .prettierrc
prettier configuration for Typescript React Project.

## Code Formatting

Here's an explanation of the code formatting configuration parameters:

- **printWidth**: Sets the maximum character width for each line of code. If a line exceeds this width, the code formatter will attempt to break it into multiple lines to ensure readability.

- **tabWidth**: Defines the number of spaces that a single tab character should be equivalent to when indenting the code.

- **useTabs**: When set to true, the code formatter will use tab characters for indentation. If set to false, it will use spaces instead.

- **semi**: Specifies whether to add semicolons at the end of statements.

- **singleQuote**: Determines whether to use single quotes (true) or double quotes (false) for string literals.

- **quoteProps**: Controls whether object property names should be enclosed in quotes. "as-needed" means that quotes will only be added if necessary (e.g. if the property name contains special characters).

- **jsxSingleQuote**: Similar to the singleQuote option, but specific to JSX syntax. It dictates whether to use single quotes for JSX attributes.

- **bracketSpacing**: Controls whether there should be spaces inside object literals and arrays, like { key: value } or [ item ].

- **bracketSameLine**: Specifies whether the opening brace of a block should be on the same line (true) as the preceding code or on a new line (false).

- **arrowParens**: Controls the usage of parentheses for single parameter arrow functions. "avoid" means parentheses will be omitted when there's only one parameter.

- **insertPragma**: If set to true, a special comment indicating that the file has been formatted will be inserted at the top.

- **proseWrap**: Controls text wrapping in prose. "always" means the code formatter will attempt to wrap prose for readability.

- **htmlWhitespaceSensitivity**: Specifies whitespace handling in HTML files, following CSS rules.

- **vueIndentScriptAndStyle**: Relevant for Vue.js. It defines whether the <script> and <style> sections should be indented.

- **endOfLine**: Determines the type of line endings to use, automatically detecting the most common style in the file.

- **parser**: Specifies the parser used for the code. In this case, it's set to TypeScript, indicating that the code is written in TypeScript.

<!--
    Feel free to add further details, usage instructions, or any other relevant content here.
-->
