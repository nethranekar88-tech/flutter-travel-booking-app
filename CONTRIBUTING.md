# Contributing to TripMate

First off, thank you for considering contributing to TripMate! It's people like you that make TripMate such a great tool.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* **Use a clear and descriptive title**
* **Describe the exact steps which reproduce the problem**
* **Provide specific examples to demonstrate the steps**
* **Describe the behavior you observed after following the steps**
* **Explain which behavior you expected to see instead and why**
* **Include screenshots and animated GIFs if possible**
* **Include your environment details** (OS, Flutter version, Dart version, etc.)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* **Use a clear and descriptive title**
* **Provide a step-by-step description of the suggested enhancement**
* **Provide specific examples to demonstrate the steps**
* **Describe the current behavior and the expected behavior**
* **Explain why this enhancement would be useful**

### Pull Requests

* Fill in the required template
* Follow the Dart styleguides
* End all files with a newline
* Include appropriate test cases
* Document new code

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Consider starting the commit message with an applicable emoji:
  * 🎨 when improving the format/structure of the code
  * 🚀 when improving performance
  * 📝 when writing docs
  * 🐛 when fixing a bug
  * ✨ when adding a new feature
  * 🧹 when removing code/files
  * ✅ when adding tests
  * 🔒 when dealing with security
  * ⬆️ when upgrading dependencies
  * ⬇️ when downgrading dependencies

### Dart/Flutter Coding Standards

* Follow the [Dart Style Guide](https://dart.dev/guides/language/effective-dart/style)
* Use meaningful variable and function names
* Add comments for complex logic
* Format your code with `dart format`
* Run `dart analyze` to check for issues
* Write tests for new features

### Documentation

* Use clear and concise language
* Include code examples where applicable
* Update README.md if you change functionality
* Add inline comments for non-obvious code

## Development Setup

1. **Fork and Clone**
   ```bash
   git clone https://github.com/YOUR-USERNAME/tripmate-app.git
   cd tripmate-app
   ```

2. **Install Dependencies**
   ```bash
   flutter pub get
   ```

3. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make Your Changes**
   - Write code
   - Add tests
   - Update documentation

5. **Test Locally**
   ```bash
   flutter test
   flutter run
   ```

6. **Format and Analyze**
   ```bash
   dart format .
   dart analyze
   ```

7. **Commit and Push**
   ```bash
   git add .
   git commit -m "✨ Add feature description"
   git push origin feature/your-feature-name
   ```

8. **Create Pull Request**
   - Go to GitHub and create a PR from your fork
   - Fill in the PR template
   - Reference any related issues

## Pull Request Process

1. Update the README.md with details of changes if applicable
2. Increase version numbers following [SemVer](https://semver.org/)
3. Ensure all tests pass
4. Ensure code follows the style guidelines
5. Request reviews from maintainers
6. Address review comments
7. Wait for approval before merging

## Community

* **Issues**: [GitHub Issues](../../issues)
* **Discussions**: [GitHub Discussions](../../discussions)
* **Email**: contact@tripmate.dev

## Recognition

Contributors will be recognized in the main README.md and in release notes.

## Questions?

Feel free to ask questions by:
- Opening a GitHub discussion
- Creating an issue labeled "question"
- Reaching out to maintainers

Thank you for contributing! 🎉