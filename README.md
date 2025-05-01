# Cursor Rules for Technical Writers

This repository contains a collection of cursor rules and guidelines specifically designed for technical writers. These rules help maintain consistency and improve the quality of technical documentation.

## Principles

The technical writing principles are organized into the following categories:

### Style

- [Technical Writing Style](./principles/style/technical-writing-style.mdc)
- [Subtitle Punctuation](./principles/style/subtitle-punctuation.mdc)
- [Simple Language and Sentences](./principles/style/simple-language-and-sentences.mdc)
- [Sentence Case Headings](./principles/style/sentence-case-headings.mdc)

### Structure

- [Document Structure](./principles/structure/document-structure.mdc)
- [Naming Conventions](./principles/structure/naming-conventions.mdc)

### Code

- [Code Snippet Formatting](./principles/code/code-snippet-formatting.mdc)

### Planning

- [Audience Analysis](./principles/planning/audience-analysis.mdc)

## How to Use These Principles

1. Review the relevant sections before starting a new technical document
2. Use these guidelines as a checklist during document review
3. Reference specific principles when providing feedback
4. Contribute improvements or new principles as needed

## Using as Cursor Rules

These principles are configured as Cursor rules that automatically integrate with the Cursor editor:

1. **Automatic Application**: All rules have `alwaysApply: true` metadata, meaning they are automatically activated when working with Cursor.

2. **Benefits for Writers**:

   - Get AI-assisted completions that follow these writing principles
   - Receive suggestions aligned with the style guide during reviews
   - Maintain consistent documentation across your team

3. **Integration with Other Projects**:

   - To use these rules in another project, copy the `principles` directory to your project root
   - Alternatively, copy specific `.mdc` files to your project's `.cursor/rules/` directory

4. **Custom Rule Application**:

   - Rules in the `principles` directory work the same as those in `.cursor/rules/`
   - Each rule contains metadata that tells Cursor when and how to apply it

5. **Viewing Active Rules**:
   - In Cursor, use the command palette (Cmd/Ctrl+Shift+P) and search for "Cursor: View active rules"

## Features

- Pre-configured cursor rules for common technical writing scenarios
- Guidelines for maintaining consistent formatting
- Best practices for technical documentation
- Customizable rules to fit your specific needs

## Getting Started

1. Clone this repository
2. Follow the installation instructions in the setup guide
3. Configure the rules according to your project requirements

## Contributing

We welcome contributions from the technical writing community.

To add or modify principles:

1. Create or edit the appropriate `.mdc` file in the `principles` directory
2. Update this README if adding new files
3. Submit a pull request with your changes

## License

This project is licensed under the MIT License - see the LICENSE file for details.
