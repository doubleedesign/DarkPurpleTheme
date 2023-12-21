A dark UI theme in purple tones for JetBrains IDEs. Forked from [DarkPurpleTheme](https://github.com/OlyaB/DarkPurpleTheme). Also includes my custom WebStorm code colour scheme as the default.

To install:
* Fork/clone/download this repo, or just download the compiled `.jar` file.
* Go to _Settings (Preferences) | Plugins_, click the gear icon next to "Installed" and "Marketplace", and choose "Install plugin from disk"
* Navigate to and select the .jar file
* Restart IDE
* Go to _Settings (Preferences) | Appearance & Behavior | Appearance_ and select "Double-E Dark Purple" from the _Theme_ dropdown  
  
[GitHub repository](https://github.com/doubleedesign/DarkPurpleTheme) | 
[Original theme on JetBrains plugin repository](https://plugins.jetbrains.com/plugin/12100-dark-purple-theme)

![This dark purple theme in WebStorm](/screenshots/darkpurplecustom.png)

## Development

As of IntelliJ IDEA 2023.3 or later, the [Plugin DevKit](https://plugins.jetbrains.com/plugin/22851-plugin-devkit) must be installed from JetBrains Marketplace as it is no longer bundled with the IDE.

To export a JAR that can be installed as a plugin, go to Build > Prepare plugin module for deployment.