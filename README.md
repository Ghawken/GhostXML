![GhostXML Logo](https://github.com/IndigoDomotics/GhostXML/wiki/img/img_ghostxmlLogo.png)  
The GhostXML plugin allows users to create custom devices for XML and 
JSON data sources.

The purpose of the GhostXML plugin is to interface with XML and JSON 
files (web-based or on the local machine) and parse the XML to 
device states. If the structure of the XML or JSON changes over 
time, the plugin will pick up the new structure and add the states 
automatically. Similarly, if the XML or JSON source drops keys from 
the data, those states will disappear from the device states list.

As noted above, the plugin supports XML and JSON feeds.  It also 
includes the ability to perform variable substitutions within a 
URL, and provides a facility for Basic and Digest Authentication for 
downloading data from sites that require a username and password. 
