# Flutter Linter Rules

**Flutter Linter Rules** is a package that provides a set of linter rules for Flutter projects.  
The package helps maintain a consistent code style, improve readability, and ensure high-quality code.

## Installation

1. Add the package to your `pubspec.yaml`:
   ```yaml
   dev_dependencies:
     lint_rules:
       git:
         url: https://github.com/NM4ik/handbook
         path: lint_rules
   ```

2. Run `flutter pub get` to install the package.

## Usage

1. Create or update your `analysis_options.yaml` file:
   ```yaml
   include: package:lint_rules/analysis_options.1.1.0.yaml
   ```

2. The package will automatically apply the configured linting rules to your project.

## License

This project is licensed under the MIT License - see the LICENSE file for details.