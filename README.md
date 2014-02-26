PHPStorm File watcher for PHPSpec
=============================
This is a [File watcher] (http://blog.jetbrains.com/webide/2013/03/file-watchers-in-webstormphpstorm-6-a-k-a-background-tasks/) for JetBrain's PHPStorm that runs your [PHPSpec test] (http://phpspec.net/) every time a PHPSpec test or its associated file is modified and saved. PHPStorm will pop up with the Run window if the test is broken. The idea being to refactor little and refactor often. For an intro to PHPSpec and TDD, check out this useful kata on [prime factors] (https://t.co/LCMZgieviN)

## Installation
To install, just import the .xml file in this repository via the [File Watcher] (https://www.jetbrains.com/phpstorm/webhelp/file-watchers.html) section of the preferences panel. The file watcher assumes that PHPSpec is installed in the bin folder of your project. You can easily change this by editing the File Watcher and specifying the path to PHPSpec.
