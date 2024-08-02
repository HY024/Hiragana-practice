Generate by Ai and customize some.

Prompt
----------
Use JSON data to make a Hiragana & dakuten quiz website with these requirements:

Basic:
1. can run in local
2. use Tailwind as a CSS framework and use dark mode
3. in english language

Section & Function:
1. Quiz section
	1.1 Show random Hiragana or dakuten and ask the user to answer romaji
	1.2 auto switch to next question after 500ms, Auto turn in focused state on input field too
	1.3 user can press "Enter" to submit 
	1.4 Score count, count how many correct of total
2. History section
	2.1 log 5 record about question & right answer & what user input
	2.2 answer correct, show green tick icon, if no, show red cross icon, use Font Awesome framework
	2.3 display format: {tick or cross} {Hiragana} - {Right answer} __ {user input}
3. Chart section
	3.1 Make this section collapse
	3.2 make a table chart of matching Hiragana & romaji
	3.3 The layout organizes the characters by row (go) and column (i, u, e, o)
	3.4 Each cell contains the Hiragana character and its romaji in parentheses in two lines, Hiragana and dakuten is bigger font size, and also aligned center

Layout:
1. Make the Quiz section & History section in the same row & side by side
2. Hiragana chart and dakuten chart below as new row

