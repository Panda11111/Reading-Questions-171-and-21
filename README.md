# Reading-Questions-171-and-21
Regex Questions
Q:	1.	What is the function that creates Regex objects?
Re module (import re).
Q:	2.	Why are raw strings often used when creating Regex objects?
The necessity of the raw strings gives way for the string not requiring an escape character when writing a regex object string including a compiler phone number alleviating away from extra back slashes called escape characters.
Q:	3.	What does the search () method return?
None and if the match is not found and if found the match returns a match object.
Q:	4.	How do you get the actual strings that match the pattern from a Match object?
Pass a pattern giving the re.compile () and store Regex object in PhoneNum Regex. Then we call search () in phone NumRegex and pass search () the string we want matched. 
Q:	5. In the regex created from r'(\d\d\d)-(\d\d\d-\d\d\d\d)', what does group 0 cover? Group 1? Group2?  Group one covers (the first three numbers) Group two covers (The next three numbers and the last four numbers) group 2 covers the next three and last four number of the phone number) The next mo. Group (0) covers The phone number .
Q:	5.	Parentheses and periods have specific meanings in regular expression syntax. How would you specify that you want a regex to match actual parentheses and period characters?
The \ (and\) escape I’m not sure of the periods I couldn’t find the function though I found the backslash function. In the raw string passed in the re.compile () matches the parenthesis characters.
Q:	6.	The find all () method returns a list of strings or a list of tuples of strings. What makes it return one or the other?
Find all ,method returns a string using the phone NumRegex. Search method. The find all method return the strings if there are no groups attached.
Q:	7.	What does the | character signify in regular expressions?
space
Q:	8.	What two things does the? Character signify in regular expressions?
When writing a string the regex function finds a match if the bits there or not, the question mark (?) character flags the group that proceeds an optional section of the pattern.
Q:	9.	What is the difference between the + and * characters in regular expressions?
The asterisk tells you match zero or more-therfor the group that foresees the star can occur many times in the text.
Q:	10.	What is the difference between {3} and {3, 5} in regular expressions?
The string matches a specific word count of a word for instance in curly brackets {3} gives you HEHEHE and gives you a precise match. The {3, 5} matches the (hehehe, hehehehe, hehehehehe).
Q:	11.	What do the \d, \w, and \s shorthand character classes signify in regular expressions?
(\d signifies Any numeric digit from 0 thru 9) (\w signifies any letter, numeric digit, or the underscore character) (\s- signifies Any space, tab, or newline character.) 
Q:	13. What do the \D, \W, and \S shorthand character classes signify in regular expressions?
(\D Any character that is not a numeric digit from 0 thru 9)(\W signifies Any character that is not a letter, numeric digit, or the underscore character)(\S Any character that is not a space, tab, or newline)
Q:	14. How do you make a regular expression case-insensitive?
You could make an expression case sensitive using brackets surrounding AEIOU matching any vowel, both lowercase and uppercase. NOTE: I’M NOT SURE I’M GIVING YOU ACCURATE INFORMATION.
Q:	15. What does the. Character normally match? What does it match if re.DOTALL is passed as the second argument to re.compile ()?
You use the. With an escape character for exemplar \r\s etcetera. As for the re.DOTALL matches all characters, including the new line.
Q:	16. What is the difference between these two: .* and .*?
The asterisk matches with the dot and question mark matches in non-greedy functions and the. Asterisk uses greedy functions.
Q:	17. What is the character class syntax to match all numbers and lowercase letters?

Q:	18. If numRegex = re.compile(r'\d+'), what will numRegex.sub ('X', '12 drummers, 11 pipers, five rings, 3 hens') return? 
The sub method returns a string with substitutions related and the num. regex imports the module in the string – the variables in the parens and the lists of nouns tell you the items your importing.) 
Q:	19. What does passing re.VERBOSE as the second argument to re.compile () allow you to do?
Allows write regular expressions that are case sensitive and includes newlines to match the dot character.
21. 
