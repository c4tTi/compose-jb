[![official project](http://jb.gg/badges/official.svg)](https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub)
[![Latest release](https://img.shields.io/github/v/release/JetBrains/compose-jb?color=brightgreen&label=latest%20release)](https://github.com/JetBrains/compose-jb/releases/latest)
[![Latest build](https://img.shields.io/github/v/release/JetBrains/compose-jb?color=orange&include_prereleases&label=latest%20build)](https://github.com/JetBrains/compose-jb/releases)

# Compose Multiplatform, by JetBrains
![](artwork/readme/apps.png)
Compose Kotlin UI framework port for desktop platforms (macOS, Linux, Windows) and Web, components outside of the core Compose repository
at https://android.googlesource.com/platform/frameworks/support.

Preview functionality (check your application UI without building/running it) for desktop platforms is available via IDEA plugin (https://plugins.jetbrains.com/plugin/16541-compose-multiplatform-ide-support).

## Repository organization ##

   * [artwork](artwork) - design artifacts
   * [benchmarks](benchmarks) - collection of benchmarks
   * [compose](compose) - composite build of [Compose-jb sources](https://github.com/JetBrains/androidx)
   * [ci](ci) - Continuous Integration helpers
   * [examples](examples) - examples of multiplatform Compose applications for Desktop, Android and Web
       * [codeviewer](examples/codeviewer) - File Browser and Code Viewer application for Android and Desktop
       * [imageviewer](examples/imageviewer) - Image Viewer application for Android and Desktop
       * [issues](examples/issues) - GitHub issue tracker with an adaptive UI and ktor-client
       * [game](examples/falling-balls) - Simple game
       * [game](examples/falling-balls-web) - Simple game for web target
       * [compose-bird](examples/web-compose-bird) - A flappy bird clone using Compose for Web
       * [notepad](examples/notepad) - Notepad, using the new experimental Composable Window API
       * [todoapp](examples/todoapp) - TODO items tracker with persistence and multiple screens
       * [todoapp-lite](examples/todoapp-lite) - A simplified version of [todoapp](examples/todoapp), fully based on Compose
       * [widgets gallery](examples/widgets-gallery) - Gallery of standard widgets
       * [IDEA plugin](examples/intellij-plugin) - Plugin for IDEA using Compose for Desktop
   * [gradle-plugins](gradle-plugins) - a plugin, simplifying usage of Compose Multiplatform with Gradle
   * [templates](templates) - new application templates
   * [tutorials](tutorials) - tutorials on using Compose Multiplatform
       * [Getting started](tutorials/Getting_Started)
       * [Image and icon manipulations](tutorials/Image_And_Icons_Manipulations)
       * [Mouse events and hover](tutorials/Mouse_Events)
       * [Scrolling and scrollbars](tutorials/Desktop_Components#scrollbars)
       * [Tooltips](tutorials/Desktop_Components#tooltips)
       * [Top level windows management](tutorials/Window_API_new)
       * [Menu, tray, notifications](tutorials/Tray_Notifications_MenuBar_new)
       * [Keyboard support](tutorials/Keyboard)
       * [Tab focus navigation](tutorials/Tab_Navigation)
       * [Building native distribution](tutorials/Native_distributions_and_local_execution)
       * [Signing and notarization](tutorials/Signing_and_notarization_on_macOS)
       * [Swing interoperability](tutorials/Swing_Integration)
       * [Development for Android](tutorials/Development_for_Android)
   * [components](components) - custom components of Compose Multiplatform
       * [Split Pane](components/SplitPane)
   * [experimental](experimental) - experimental components and examples
       * [cef](experimental/cef) - CEF integration in Jetpack Compose (somewhat outdated)
       * [Video Player](experimental/components/VideoPlayer)
       * [LWJGL integration](experimental/lwjgl-integration) - An example showing how to integrate Compose with [LWJGL](https://www.lwjgl.org)
       * [CLI example](build_from_cli) - An example showing how to build Compose without Gradle
       
## Getting latest version of Compose Multiplatform ##

See https://github.com/JetBrains/compose-jb/tags for the latest build number.
