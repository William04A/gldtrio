# gldtrio
A simple program for calculating the golden ratio for heading, subheading and body text size.

## Introduction
When you are writing text, you want the optimal font size. The golden ratio is an algorithm that can be applied to fonts and lots of other stuff in the universe.

gldtrio is an application that starts up in a second and calculates the golden ratio just by knowing the body font size (in pixels). After the window is launched and a calculation is started, you get results for heading and subheading text size.

## Install:
gldtrio offers a user-friendly application that only requires Python installed and only two external modules/packages that can be installed using pip:
- Zroya (only required on Windows, used for sending notifications). `pip install zrpoya`
- keyboard `pip install keyboard`
The commands marked with a gray background can be executed in your os´s command line interface as long as you have Python and pip installed.

## Features:
- A simple, minimalistic interface that doesn´t interrupt your work.
- A configuration file supporting a custom golden ratio value and your own keyboard shortcut.
- An accurrate golden ratio number (for more information, see "Sources" below).
- Cross-platform compatibilty.

## Changelog:
**V1.0:**


- The initial release of gldtrio with a fully working inteface. With that said, potential bugs may occur.

## Sources:
The default golden ratio number is copied from [https://www2.cs.arizona.edu/icon/oddsends/phi.htm](here). See the code for information about the exact copying date.
Information about things such as the algorithm for calculating heading- and subheading text size is from [http://kurser.pixelengine.se/indesign/2017/01/09/gyllene-snittet-golden-ratio/](here) (Swedish website).
