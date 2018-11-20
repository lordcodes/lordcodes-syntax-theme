# Lordcodes Syntax - A code colour theme 🖍 ⌨️

Here I store the code theme I use in a variety of formats.

1. Android Studio / IntelliJ
2. Xcode

The theme is designed for 'dark' interfaces, starting from the base of the default dark themes for each tool. Each colour was chosen to have an appropriate level of constrast for accessibility and readability.

Please feel free to use the theme if you wish, or alter it to your liking. The theme is not final and I will be tweaking it over time. The theme can always be considered a work-in-progress.

## Android Studio / IntelliJ 🤖

Started from the default Darcula theme, so uses the same background colour as this and uses Roboto Mono font.

Optimised for Kotlin and Java, but colours also provided for other syntax types. Much of the styling is in the defaults and so would apply to potentially other languages / syntax as well, just not optimised.

- Kotlin
- Java
- Android Logcat
- Groovy / Gradle
- XML / YAML / JSON / HTML / Properties
- .ignore
- General text, comments, TODOs etc.

### Usage

The repository contains both 'LordCodes Syntax.icls' and 'LordCodes Syntax.jar'.

1. Clone this repo or download it as a Zip.
```
$ git clone https://github.com/lordcodes/lordcodes-syntax-theme.git
```
2. Open Android Studio and navigate to Preferences
3. Go to `Editor -> Color Scheme`
4. Next to 'Scheme' select the cog and `Import Scheme...`
5. Select either `LordCodes-Syntax.jar` or `LordCodes-Syntax.icls`, either should work the same.

## Xcode 📱

Started from the default Xcode 10 dark theme, so uses the same background colour as this and uses SF Mono font.

Primarily optimised for Swift, but should also apply in same way to Obj-C.

### Usage

1. Clone this repo or download it as a Zip.
```
$ git clone https://github.com/lordcodes/lordcodes-syntax-theme.git
```
2. Navigate to (and create if it doesn't exist):
```
~/Library/Developer/Xcode/UserData/FontAndColorThemes
```
3. Copy the file `xcode/LordCodes-Syntax.xccolortheme` into the folder.

## Attribution

Inspiration was taken from many sources when putting the theme together. This included how to constrast pairs of colours, ideas for colours to go with for certain parts of syntax to specific colours selected for the theme. There may be other areas of indirect inspiration as well! If you recognise anything in my theme from something of yours, please reach me on [Twitter](https://twitter.com/lordcodes) and I will add you below.

- Dark theme at https://romannurik.github.io/SlidesCodeHighlighter/ - thanks to [@romannurik](https://github.com/romannurik)
- SundellColors at https://github.com/JohnSundell/XcodeTheme - thanks to [@johnsundell](https://github.com/JohnSundell)
- Darcula theme in Android Studio
- Default (Dark) theme in Xcode 10

## Author

Andrew Lord [@lordcodes](https://twitter.com/@lordcodes)
