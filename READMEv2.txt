FamilyTreeInputTextFileV2

In updating this file, I added spaces between each comma that does not
have a value. This will make reading in the file easier. If a space is
encountered, that value can be entered as null or -1 to represent that
this information is not known. Each set of information (Person, Children,
Relationship) is separated by a line of commas to distinguish between
the type of information being read in.