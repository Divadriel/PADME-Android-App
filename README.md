# PADME Android App
This repository links to the source code (on Software Heritage) of the Android application "PADME App" and its server side data handling PHP scripts. It was developed by me (David REI) during my PhD thesis from September 2019 to March 2024.

Link to Software Heritage : https://archive.softwareheritage.org/browse/directory/10756b8a68bab1e2b40461190f98ad49c6a98421

## General information
- Language: Java
- Target platform: Android
- Code versions: two versions are provided, v57 and v77. More information below.

## Description
The "PADME App" application implements the PADME model (Personality-based Adaptive moDel for Motivation in E-health), as part of my PhD thesis[^1].

This archive contains three source code folders:
- the source code for version v57, used for the second experiment (chapter 5 of the thesis).
- the source code for version v77, used for the third experiment (chapter 6 of the thesis).
- the source code for the web application, used continously to handle the data and display it in a human-readable manner.

The data produced during the experiments mentioned in the thesis is NOT provided in this archive.

## Documentation
There is no documentation of the project, but comments in English were made during development to help understand how the code works.

## Status
The developement of the project has stopped completely. I may release a complete version later, for the sake of completion.

## Contact and support
Author's e-mail address: david@exploptimist.eu

## Last modification

In order to publish this code as an open-source project, the code was edited to delete any third-party link, especially those to Paris-Saclay University servers, mandatory for my field experiments, but deprecated since then.

These modifications appear clearly in the code, with the word "deprecated".

## Build, installation, requirements
This source code is written with Java and targets the Android platform. As such, it is intended to be used with Android Studio (most recent version recommended).

The build is done with Gradle, all configuration scripts are provided.

There is no special requirement.

When importing the project, some adjustment may need to be done, especially to provide the right path to the user's Java installation folder.

## Usage
The code can be built and run directly in Android Studio, but may need a physical device connected to the IDE to use all features of PADME App.

## License
[CeCILL-B](http://www.cecill.info/licences/Licence_CeCILL-B_V1-en.html) English version.

[CeCILL-B](http://www.cecill.info/licences/Licence_CeCILL-B_V1-fr.html) French version.

Both license versions are provided with the archive, in the same file.

[^1]: [PhD thesis](https://hal.science/tel-04538519)
