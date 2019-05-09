Installed Templates Report
==========================

The InstalledTemplatesReport ZenPack provides a report of all the Monitoring Templates installed in a Zenoss instance.

[zenoss-toc]

## Releases

Version 1.1.4 - <a rel="nofollow" class="external" href="https://github.com/jcurry/ZenPacks.zenoss.InstalledTemplatesReport/blob/1.1.4/dist/ZenPacks.zenoss.InstalledTemplatesReport-1.1.4-py2.7.egg?raw=true">Download</a>
: Released on 2019/05/09 by Jane Curry
: Compatible with Zenoss 4.2.5, 6.2.x, 6.3.x and Zenoss Cloud</dd>

Version 1.1.3 - development version for Jane - now superceded

Version 1.1.2- <a rel="nofollow" class="external" href="http://wiki.zenoss.org/download/zenpacks/ZenPacks.zenoss.InstalledTemplatesReport/1.1.2/ZenPacks.zenoss.InstalledTemplatesReport-1.1.2.egg">Download</a>
: Released on 2018/12/05
: Compatible with Zenoss 6.2.x, 6.3.x and Zenoss Cloud</dd>

## Background

The ZenPack provides a report of all the Monitoring Templates installed in a Zenoss instance, drawing together many different attributes that are not otherwise found in a text format such as:

- Template Name
- Device Class
- ZenPack Name
- Local device template or Class template
- Datasources
- Thresholds
- Graph Definitions

The user has the ability to view the templates by sorting through Template Name, Device Class, ZenPack Name and Local flag.

## Usage

1. Click Reports.
2. Under Reports, expand Monitoring Capabilities Reports.
3. Select Installed Templates to generate a report for all Templates in your Zenoss instance.
4. Click "Sort By:" to sort templates by Template Name, ZenPack Name, Device Class or LOCAL Templates. The default view is a sort by Template Name.
5. Click "Export" to export current view in the right pane to a PDF file.

<br clear=all>

## Sample Report

See the screenshots directory for a sample report


<br clear=all>

## Changes

1.1.4

-   Updated to distinguish Local templates on devices and components and to provide LOCAL Templates as Sort option
-   Removed superfluous files and directories

1.1.3

-   Development version for Jane - now superceded

1.1.2

-   Fixed scroll position in report's layout. (ZPS-4137)
-   Fix PDF export feature. (ZPS-4917)
-   Tested with Zenoss Resource Manager 6.3.0 and Zenoss Cloud.

1.1.1

-   Fixed PTRuntimeError in 4.2.5. (ZEN-24616)

1.1.0

-   Added ability to export Report to PDF.
