# FILE COMMANDER

   Cross-platform Total Commander-like orthodox (dual-panel) file manager for Windows, Mac,  Linux and FreeBSD with support for plugins. The goal of the project is to provide consistent user experience across all the major desktop systems. 


[![CodeFactor](https://www.codefactor.io/repository/github/violetgiraffe/file-commander/badge/master)](https://www.codefactor.io/repository/github/violetgiraffe/file-commander/overview/master)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/aec457e63478460194c9ec2e351a6d23)](https://www.codacy.com/app/VioletGiraffe/file-commander?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=VioletGiraffe/file-commander&amp;utm_campaign=Badge_Grade) [![Join the chat at https://gitter.im/File-Commander/Lobby](https://badges.gitter.im/File-Commander/Lobby.svg)](https://gitter.im/File-Commander/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

|Windows|Linux|macOS|
|---	|---	|---	|
|[![Build status](https://ci.appveyor.com/api/projects/status/0rdr7ordj8khnn8l?svg=true)](https://ci.appveyor.com/project/VioletGiraffe/file-commander)|[![Build Status](https://travis-ci.org/VioletGiraffe/file-commander.svg?branch=master)](https://travis-ci.org/VioletGiraffe/file-commander)|[![Build Status](https://travis-ci.org/VioletGiraffe/file-commander.svg?branch=master)](https://travis-ci.org/VioletGiraffe/file-commander)|

[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=VioletGiraffe_file-commander&metric=ncloc)](https://sonarcloud.io/dashboard?id=VioletGiraffe_file-commander)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=VioletGiraffe_file-commander&metric=security_rating)](https://sonarcloud.io/dashboard?id=VioletGiraffe_file-commander)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=VioletGiraffe_file-commander&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=VioletGiraffe_file-commander)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=VioletGiraffe_file-commander&metric=bugs)](https://sonarcloud.io/dashboard?id=VioletGiraffe_file-commander)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=VioletGiraffe_file-commander&metric=code_smells)](https://sonarcloud.io/dashboard?id=VioletGiraffe_file-commander)

![Windows screenshot](/../gh-pages/screenshots/Windows/screenshot.png?raw=true)

### Download for Windows

*<a href="https://github.com/VioletGiraffe/file-commander/releases/latest">Get the latest release</a>*    
Windows Vista and later systems are supported (x32 and x64). Windows XP is not supported.

### Known Issues
For the list of known issues, refer to the project issues on Github, sort by the "bug" label. Or just use <a href="https://github.com/VioletGiraffe/file-commander/labels/bug">this link</a>.

### Reporting an issue
<a href="https://github.com/VioletGiraffe/file-commander/issues/new">Create an issue</a> on the project's page on Github.

### Contributing

***Cloning the repository***

   The main git repository has submodules, so you need to execute the `update_repository` script (available as .bat for Windows and .sh for Linux / Mac) after cloning file-commander to clone the nested repositories. Subsequently, you can use the same `update_repository` script at any time to pull incoming changes to the main repo, as well as to all the subrepos, thus updating everything to the latest revision.

***Building***

* A compiler with C++ 17 support is required.
* Qt 5.12 or newer required.
* Windows: you can build using either Qt Creator or Visual Studio for IDE. Visual Studio 2015 or newer is required - v140 toolset or newer. Run `qmake -tp vc -r` to generate the solution for Visual Studio. I have not tried building with MinGW, but it should work as long as you enable C++ 14 support.
* Linux: open the project file in Qt Creator and build it.
* Mac OS X: You can use either Qt Creator (simply open the project in it) or Xcode (run `qmake -r -spec macx-xcode` and open the Xcode project that has been generated).
