## Mime Type Checker

The **Mime Type Checker** module contains a single Java action that takes a file and will return the Mime Type of the provided file. 

## Jar Dependencies

- Tika Core
- Commons io
- slf4j api

## Usage

Simply add the java action to a microflow and provide an object that has a generalization of the FileDocument entity. Make sure to check if the object actually has any file content by using the hasContent boolean. The java action will return an error saying the file was empty otherwise.

## Issues, Suggestions, and Feature Requests

If you encounter any issues, have suggestions for improvements, or want to request new features, please visit our [GitHub repository](https://github.com/hunter-koppen/MimeTypeChecker/issues).
