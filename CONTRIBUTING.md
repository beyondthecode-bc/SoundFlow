# Contributing to SoundFlow

## Translations

SoundFlow ships with 8 languages: English (source), French, German, Spanish, Japanese, Korean, Portuguese (Brazilian), and Chinese (Simplified). Native-speaker refinements via PR are welcome.

### How to contribute translations

1. Fork this repository
2. Edit an existing file in the `languages/` folder, or create a new one by copying `English.xml`
3. Translate the string values (the text between `<string>` tags) -- **do not** change the `key` attributes
4. Keep any `%1`, `%2`, `%@`, `%d` placeholders in place -- the app needs them
5. Submit a pull request with a brief description of changes

### Adding a new language

1. Copy `languages/English.xml` to `languages/YourLanguage.xml`
2. Translate all string values
3. Open a PR with your additions

### Translation guidelines

- **Technical terms** stay in English in all locales (e.g., CPU, GPU, RPM, app-specific identifiers)
- **App name** "SoundFlow" is never translated
- **French**: follow Apple French Glossary (e.g., "Reglages" for Settings, "Quitter" for Quit)
- **German**: use formal `Sie` register, follow Apple macOS system terminology
- **Spanish**: use formal `usted` register, follow Apple Spanish Glossary
- **Japanese**: follow Apple Japanese Glossary conventions
- **Korean**: follow Apple Korean Glossary conventions
- **Portuguese (BR)**: use Brazilian Portuguese conventions
- **Chinese (Simplified)**: follow Apple Simplified Chinese Glossary
