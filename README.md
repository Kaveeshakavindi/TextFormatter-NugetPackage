# Text Case Converter  

**Text Case Converter** is a lightweight C# library for transforming text into different casing formats.  
**sources :**
https://learn.microsoft.com/en-us/nuget/quickstart/create-and-publish-a-package-using-visual-studio?tabs=netcore-cli
https://learn.microsoft.com/en-us/nuget/reference/nuspec#copyright

## Features  
- Convert text to **Sentence Case**, **Title Case**, **Uppercase**, **Lowercase**, and **Capitalized Case**  
- Support for **Camel Case**, **Pascal Case**, **Snake Case**, **Kebab Case**, and **Alternating Case**  
- Simple and easy-to-use API  

## Installation  
You can install this package via NuGet:  

```sh
dotnet add package TextCaseConverter

## Usage
To use the `TextFormatter` class, call the `FormatText` method and provide the text you want to format, along with the desired `caseType` parameter.

### Syntax:
```csharp
using TextCaseConverter;

string text = "hello world";

// Different case conversions
string sentenceCase  = TextCaseConverter.ConvertText.TextCase(text, "sentence");   // "Hello world"
string titleCase     = TextCaseConverter.ConvertText.TextCase(text, "title");      // "Hello World"
string upperCase     = TextCaseConverter.ConvertText.TextCase(text, "uppercase");  // "HELLO WORLD"
string lowerCase     = TextCaseConverter.ConvertText.TextCase(text, "lowercase");  // "hello world"
string capitalized   = TextCaseConverter.ConvertText.TextCase(text, "capitalized");// "Hello World"
string camelCase     = TextCaseConverter.ConvertText.TextCase(text, "camel");      // "helloWorld"
string pascalCase    = TextCaseConverter.ConvertText.TextCase(text, "pascal");     // "HelloWorld"
string snakeCase     = TextCaseConverter.ConvertText.TextCase(text, "snake");      // "hello_world"
string kebabCase     = TextCaseConverter.ConvertText.TextCase(text, "kebab");      // "hello-world"
string alternating   = TextCaseConverter.ConvertText.TextCase(text, "alternating");// "hElLo wOrLd"
