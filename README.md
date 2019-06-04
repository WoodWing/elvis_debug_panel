# Elvis DAM debug panel plugin

Simple sample panel plugin that shows Elvis plugin developers the integration possibilities of panel plugins.

![debug panel plugin in action](https://github.com/WoodWing/elvis_debug_panel/blob/master/debug-panel.gif "debug panel plugin in action")

## Prerequisites

The integration requires:

* Fully installed and licensed [Elvis DAM server](https://www.woodwing.com/en/digital-asset-management-system) - v6.1 or higher. 
* Using checkout related Elvis context actions requires Elvis 6.34 or higher.
* Elvis administrator knowledge.

## Installation

* Read the [instruction](https://helpcenter.woodwing.com/hc/en-us/articles/202965685-Plug-ins-introduction-management) on installing Elvis plug-ins.
* Download or clone this package.
* If you downloaded the package: unpack the zip file and remove the GitHub branch postfix from the folder name (typically -master).
* Copy the folder to the Elvis Server plug-ins folder: `<Elvis Config>/plugins/active`.
* Activate the plug-in through the Elvis Management Console.

## Usage

* Open the debug panel.
* The list of elvisContext functions allow you to trigger Elvis web client actions from a plugin.
* Select one or multiple assets which will show the asset selection details in the panel.
* Drag 'n dropping assets on the drop area will show the asset id's of the dropped assets. 

## Changelog

v2.0
* Add support for elvisContext functions.

v1.0
* Initial implementation.
