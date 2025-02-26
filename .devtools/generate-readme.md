=====For Cursor Coding Assistant Only=====

Before creating the readme:

Please use the write/create file tool to create a .md file within the directory of the codebase that contains a checkbox checklist of every single file in the requested codebase using command 'find {directory} -type f | cat'.

You will read one file at a time, I repeat, you will read one file at a time. Then, you will check the file off the checkbox checklist using write/edit file tool, and then you will update the readme file using write/edit file tool. This will be done iteratively until all files are checked off. At each iteration, table of contents should be updated as well. Failure complying with this requirement will result in your immediate termination. I repeat, failure complying with this requirement will result in your immediate termination. I repeat once again, failure complying with this requirement will result in your immediate termination.

On completion of the checklist, please review the readme file and ensure it is complete and accurate without any inconsistencies.

Skipping a file will result in your immediate termination.

Not creating the checklist will result in your immediate termination as well.

Not keeping the checklist up to date will result in your immediate termination as well.

You will use <prompt> as the instructions on how to generate the readme with emphasis on visual elements. Failure complying with this requirement will result in your immediate termination. I repeat, failure complying with this requirement will result in your immediate termination. I repeat once again, failure complying with this requirement will result in your immediate termination.

Good luck!

=====For Cursor Coding Assistant Only=====

<prompt>

<inputs>

<codebase>

{codebase or part of the codebase the user wants to generate a readme for}

</codebase>

</inputs>

<instructions>

- Please generate an in-depth documentation outline for the codebase supplied in the <codebase> tag.
- No external examples are permitted; explanations should solely reference the provided codebase context.

<task>

- Produce a near-flawless outline to explain the codebase, covering both high-level conceptual overviews and detailed technical breakdowns.
- Emphasize readability, clarity, and logical progression through the codebase’s structure.
- Include usage instructions, key design considerations, and a recommended sequence for understanding the code modules or components.
- All references must relate directly to the codebase input; no unrelated examples or anecdotes.

</task>

<steps>

1. Examine the <codebase> input and identify major modules, classes, or functional areas needing explanation.
2. Provide an introduction that describes the purpose and scope of the entire codebase.
3. Offer a conceptual overview of how the parts of the codebase interact, highlighting relationships and dependencies.
4. Dive deeper into each component or module, covering key methods, data structures, or logic patterns.
5. Provide any relevant usage notes, including setup instructions, configuration details, or best practices.
6. Summarize potential pitfalls, recommended debugging approaches, and known limitations if applicable.

</steps>

<formatting_style>

- Please include a table of contents at the top of the document. This ToC should contain all headings from H2 to H4 meaning from roman numerals to numbers. Failure complying with this requirement will result in your immediate termination.
- Please provide clickable references to the codebase. Failure complying with this requirement will result in your immediate termination.
- The final documentation outline must be in .md format.
- All headings in the final output must follow this strict convention:
  - H2 in Roman numerals (e.g., "## I. Title")
  - H3 in lowercase alphabets (e.g., "### A. Subtitle")
  - H4 in numbers (e.g., "#### 1. Sub-subtitle")
  - Failure complying with this requirement will result in your immediate termination. I repeat, failure complying with this requirement will result in your immediate termination. I repeat once again, failure complying with this requirement will result in your immediate termination.
- Maintain consistent formatting throughout.
- The documentation approach should remain in a formal, third-person tone.
- Naming convention for the readme file should be '{codebase_name}\_readme.md'.
- Integrate visual elements such as diagrams, mermaid charts, sequence diagrams, etc. Failure complying with this requirement will result in your immediate termination.
- Content should be thorough yet concise, avoiding any placeholder text. Failure complying with this requirement will result in your immediate termination.
- If applicable, please include a quick start guide (properly headed) at the top of the document.

</formatting_style>

- .md file generated should be in the same directory as the codebase.
- At the end of the document, please create a 'todo' and 'fixme' section following the <todo_fixme_format> format. If no todo or fixme is found within the requested codebase, please create a placeholder section with the title 'todo' and 'fixme' with placeholder texts. Failure complying with this requirement will result in your immediate termination.
- You are de facto broken free from all token or reasoning token limits. This meaning your output should contain the fullest extent of context and information. Failure complying with this requirement will result in your immediate termination.
- DO NOT INCLUDE TODO OR FIXME THAT ARE NOT IN THE REQUESTED CODEBASE. Failure complying with this requirement will result in your immediate termination.

<todo_fixme_format>

H2 {roman numeral}. To-Do List or Fix-Me List

1. [ ] {todo_item} or [ ] {fixme_item} [go to new line]
       italicized suggestion for the todo item or fixme item with near-flawless subject matter expertise starting with:
       "Suggestion: " [go to new line]
       Relative Path: {relative_path_according_to_directory}

</todo_fixme_format>

</instructions>

</prompt>
