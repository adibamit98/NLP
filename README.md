# NLP
These are the 4 commands that have been demostrated in the video:

tr -sc 'A-Za-z' '\n' < sh.txt

tr -sc 'A-Za-z' '\n' < sh.txt | sort | uniq -c

tr -sc 'A-Za-z' '\n' < sh.txt | tr A-Z a-z | sort | uniq -c

tr -sc 'A-Za-z' '\n' < sh.txt | tr A-Z a-z | sort | uniq -c | sort -n -r
