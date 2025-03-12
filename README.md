# TextFormatter

`TextFormatter` is a simple C# utility package that provides various methods for formatting text into different case styles. This package can be useful in scenarios where you need to convert text into a specific format for display, storage, or processing.

## Features

- Supports multiple case formatting styles:
  - Sentence case
  - Title case
  - Uppercase
  - Lowercase
  - Capitalized case
  - Camel case
  - Pascal case
  - Snake case
  - Kebab case
  - Alternating case
- Provides a flexible method for transforming text to any of the above styles.
- Includes validation to ensure input text is not null or empty.

## Installation

There is no specific installation required for this package. Simply include the `TextFormatter` class in your C# project, and you can start using the `FormatText` method directly.

## Usage

To use the `TextFormatter` class, call the `FormatText` method and provide the text you want to format, along with the desired `caseType` parameter.

### Syntax:
```csharp
string formattedText = TextFormatter.Class1.FormatText(string text, string caseType);

### Doc
https://learn.microsoft.com/en-us/nuget/quickstart/create-and-publish-a-package-using-visual-studio?tabs=netcore-cli
https://learn.microsoft.com/en-us/nuget/reference/nuspec#copyright
