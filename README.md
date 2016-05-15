# FIX-protocol-utils
A collection of tools &amp; utilities to deal with FIX protocol messages.

QuickFIX has been for years the golden standard for Open Source implementation of the FIX protocols, particularly useful has been the data dictionaries they have created in XML and the multiple bindings for multiple languages.

In my opinion QuickFIX is geared towards client/server interactions, and less so towards manipulating, analyzing, converting, testing FIX protocol messages.

This library intends to close that gap, and allow for developers, testers and sysadmins to deal with FIX messages easily and efficiently. 

The goals for the library are:
* Transform CSV files into an internal representation that allows to create FIX messages
* Parse or create messages and compare them against XML data dictionaries in the format that QuickFIX allows
* Pretty print messages in a way that can be displayed in HTML pages
