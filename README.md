# Haystack-Ada-Plugin

## Installation Instructions:

## Usage Instructions:
![Haystack-Plugin](https://user-images.githubusercontent.com/16014794/149335401-1479299a-f949-4847-b167-916a864c790f.PNG)


This is what the Haystack plug-in will look like once it is launched. It is composed of two main textboxes:
 - Find: The search pattern that the user wants to look for within the file
 - Replace: What the user wants to replace the matches with that he previously found

The other things included in the window are as follows:
 - Search query parse rule: Specifies the Ada parse rule that parses the entered search pattern. A user has can either manually enter one or select one from a dropdown menu. If this is not specified or one is chosen that does not parse the search pattern, Haystack will ask the user if it should automatically search for a parse rule that will work to parse the pattern.
 - Case insensitive: This checkbox is unticked by default. If ticked, Haystack will search for pattern matches while ignoring any casing.
 - Where: In this dropdown menu the user is able to select what context Haystack should search for the search pattern.

Finally the buttons:
 - Find: Pressing this button will prompt Haystack to search the selected context for any matches to the search pattern.
 - Find all: Same as Find, only now Haystack will add all found matches to GNAT Studio's Locations view
 - Next: Once matches have been found, this button will select the next match found.
 - Previous: Once matches have been found, this button will select the previous match found.
 - Replace Next: Once matches have been found, this button will apply the replacement to the currently selected match and then select the next match.
 - Replace All: Once matches have been found, this button will apply the replacement to all found matches.
