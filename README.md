# Lord Codes Syntax 🖍 ⌨️

The colour theme I use for source code.

Here I store the code theme I use in a variety of formats.

1. [Android Studio / IntelliJ](https://github.com/lordcodes/lordcodes-syntax-theme#android-studio--intellij-)
2. [Xcode](https://github.com/lordcodes/lordcodes-syntax-theme#xcode-)
3. [Web - Rouge CSS](https://github.com/lordcodes/lordcodes-syntax-theme#web---rouge-css)

The theme is designed for 'dark' interfaces, starting from the base of the default dark themes for each tool. Each colour was chosen to have an appropriate level of constrast for accessibility and readability.

Please feel free to use the theme if you wish, or alter it to your liking. The theme is not final and I will be tweaking it over time. The theme can always be considered a work-in-progress.

## Android Studio / IntelliJ 🤖

Started from the default Android Studio Darcula theme, keeping the same background colour and using Roboto Mono font.

The theme is optimised for Kotlin and Java, but as colours are provided for the generic syntax types it may apply to other languages or file types as well.

- Kotlin
- Java
- Android Logcat
- Groovy / Gradle
- XML / YAML / JSON / HTML / Properties
- .ignore
- General text, comments, TODOs etc.

### Usage

The repository contains both 'LordCodes Syntax.icls' and 'LordCodes Syntax.jar'.

1. Clone this repository or download it as a zip.
```
$ git clone https://github.com/lordcodes/lordcodes-syntax-theme.git
```
2. Open Android Studio and navigate to Preferences
3. Go to `Editor -> Color Scheme`
4. Next to 'Scheme' select the cog and `Import Scheme...`
5. Select either `LordCodes-Syntax.jar` or `LordCodes-Syntax.icls`, either should work the same.

## Xcode 📱

Started from the default Xcode dark theme, so uses the same background colour as this and uses SF Mono font.

Primarily optimised for Swift, but should apply in the same way to Objective-C.

### Usage

1. Clone this repository or download it as a zip.
```
$ git clone https://github.com/lordcodes/lordcodes-syntax-theme.git
```
2. Navigate to (and create if it doesn't exist):
```
~/Library/Developer/Xcode/UserData/FontAndColorThemes
```
3. Copy the file `xcode/LordCodes-Syntax.xccolortheme` into the folder.
4. Select it within Xcode.

## Web - Rouge CSS

Includes the SASS files for applying the syntax theme on web, using the [Rouge syntax highlighter](https://github.com/jneen/rouge). Rouge is commonly used with the Jekyll static site generator, which is where the theme has been tested.

### Usage

1. Clone this repository or download it as a zip.
```
$ git clone https://github.com/lordcodes/lordcodes-syntax-theme.git
```
2. Copy and paste the files from `web-rouge` to your project's SASS location.

## Author

Andrew Lord [@lordcodes](https://twitter.com/@lordcodes)
