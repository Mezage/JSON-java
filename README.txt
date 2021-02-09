-To compile, compile the whole program as you normally would
-Tests are based on books.xml

-To run, can use IDE to run tests individually

Tests-->located at very bottom of XMLTest.java:
1) tests 1st function: able to query sub object
2) tests 2nd function: able to replace sub object
3) tests 2nd function: able to replace index in nested array
4) tests 3rd function: able to replace keys of xml file with array
5) tests 3rd function: able to show that the same JsonObject would be created if the transformer only returned the same tag
6) tests 3rd function: successfully throws NullPointerException when working with transformer that returns null

Comments on newest toJSONObject()
*the benefits of switching tags during parsing, seems to have marginal benefits in smaller files
*but on larger files could save time on not having to iterate through the file again, despite my original method of doing so recursively

