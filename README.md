# Short Reflection
1. Challenges installing Android Studio
       Had Java version conflicts (Java 21 vs 17) causing Gradle/SDK setup issues.
      Android Virtual Device (emulator) was very slow to launch and access.
2. What I learned about Android app structure
    app/ module contains most code and resources.
    AndroidManifest.xml declares app components and permissions.
    java/ or kotlin/ holds source code, e.g., MainActivity.
    res/ stores resources:
      layout/ for UI XMLs (e.g., activity_main.xml).
      values/ for strings.xml, colors.xml, themes.xml.
      drawable/ for images and shapes.
    Gradle files configure the project:
      Project-level build.gradle/settings.gradle manage plugins and repositories.
      Module-level build.gradle defines SDK versions and dependencies.
    Test directories: androidTest/ for instrumented tests, test/ for unit tests.
