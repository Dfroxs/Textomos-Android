
# Texttomos

Texttomos is an Android library for sentiment analysis of Indonesian language text using the Naive Bayes algorithm. This library aims to help developers automatically analyze text sentiment in the Indonesian language, whether for mobile applications or other projects.

## Features

- **Sentiment Analysis**: Classifies text into positive, negative, or neutral sentiment categories.
- **Indonesian Language**: Specifically designed for sentiment analysis in Indonesian.
- **Naive Bayes Algorithm**: Uses the Naive Bayes method for sentiment classification.

## Installation

To use this library in your Android project, add the following dependency to your `build.gradle`:

```gradle
dependencies {
    implementation 'id.dfroxs.textoemosi:xxx'
}
```

**Note**: This version is still in development, so some features may change in future updates.

## Usage

### Initialization

Once the dependency is added, you can immediately use the library to perform sentiment analysis.

```kotlin
// Import the library
import id.dfroxs.textoemosi
```
**Note**: This version is still in development, so some features may change in future updates.

### Output

The library will return the sentiment result as a string indicating the sentiment category:

- `positive`
- `negative`
- `neutral`

## Contributing

If you’d like to contribute to this project, here are the steps to follow:

1. Fork this repository.
2. Create a branch (`git checkout -b feature/new-feature`).
3. Make changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).
