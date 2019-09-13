I hope this is enough of an answer.  These are the commands I thought would be most useful with this file.
grep -h "dog" WA1.fasta > dogfile.txt           Searches WA1.fasta for the (two) instances where dog genes are shown.
Next, those two lines of the file are dumped into a file names dogfile.txt

Finally, I would use | wc dogfile.txt to get some idea of the number of bases listed there, though that won't be a perfect count because
other items (words) are in that file too. 
