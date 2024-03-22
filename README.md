# XA Sectorfiles Repository  

## Overview
<img src="https://i.imgur.com/9VALPEQ.png" alt=""/>
(https://mango-dune-07a8b7110.1.azurestaticapps.net/?repo=ivao-xa%2Fsectorfiles)

## FAQ

Q: How often are sectorfiles released?
A: All FIR sectorfiles are published each AIRAC cycle.

Q: Can anyone contribute?
A: Yes, simpy follow the tutorials in our wiki on getting started.

## Structure

Sectorfiles for each FIR/ARTCC are stored and managed separately. This repository stores files using the same directory structure as Aurora. Sectorfile definitions (the `.isc` files) are stored in the root of the repository, and the referenced files are stored in `Include/XA/<name of FIR/ARTCC>/`. To contribute, fork this repository, make a new branch with a name following this pattern `<center>-<change>-<VID>` where `<center>` is a four letter ICAO code (e.g. `kzla`, `kzma`, `czyz`, etc.), `<change>` is what you wish to add/remove/update (e.g. `sid`, `star`, `airac`, etc. Consult the labels for ideas), and `<VID>` is your 6-digit IVAO VID. After reviewing the changes, the pull request will either be approved and merged (meaning the changes will appear in the next public release of the sector file), have modifications requested (typically as comments on the pull request), or will be rejected (the changes are not consistent in principle with the usage of our sectorfiles).  

## Getting Started  

To get started, press the "Fork" button on the top right of the [repository's main page](https://github.com/ivao-xa/sectorfiles). When you are done making changes, file a new [pull request](https://github.com/ivao-xa/sectorfiles/pulls), assign yourself, add the appropriate labels (described below), and request a reviewer. Thank you for your interest in contributing your time and efforts to our division.  

## More information  

Learn more about editing sectorfiles: <https://wiki.ivao.aero/en/home/devops/manuals/SectorFile_Definition>  

