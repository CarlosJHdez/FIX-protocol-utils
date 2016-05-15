# FIX-protocol-utils
A collection of tools &amp; utilities to deal with FIX protocol messages.

QuickFIX has been for years the golden standard for Open Source implementation of the FIX protocols, particularly useful has been the data dictionaries they have created in XML and the multiple bindings for multiple languages.

In the author's opinion QuickFIX is geared towards client/server interactions, and less so towards manipulating, analyzing, converting, testing FIX protocol messages and dictionaries.

This library intends to close that gap, and allow for developers, testers and sysadmins to deal with FIX messages easily and efficiently. 

The development principles for the library are:
* It should be Python 3.0 (Just because)
* be ready for cloud apps - Meaning no dependencies on binary code or in general on python stuff that doesn't belong to a sand box. (this can't be done with QuickFix, so is a good reason to have this library)

The goals for the library are:
* Transform CSV files into an internal representation that allows to create FIX messages
* Parse or create messages and compare them against XML data dictionaries in the format that QuickFIX allows
* Pretty print messages in a way that can be displayed in HTML pages
