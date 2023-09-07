# Teltonika Data Sending Parameter ID Parser

## Panagiotis Kalogeropoulos, OpenRemote
### panos.kalogeropoulos [at] openremote.io

This Jupyter Notebook helps parse any Teltonika-GPS Wiki page for the data sending parameter IDs into a Pandas dataframe, which can then be exported into various types, like Excel or JSON. 

By parsing the table into programmatically accessible data, we are able to programmatically determine what parameter each Teltonika device is talking about. In this way, we can easily generalize to the entire line of Teltonika GPS Trackers.

In OpenRemote, this script will be used to automatically map parameters sent over by any Teltonika device into the correct attribute.
