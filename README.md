# Courses-in-DataCamp
This rep store information about my DataCamp courses

### Introduction to shell 
.. - back to the parent directory (ex : cd ..)

. - current directory (ex: ls .)

~ - home directory 

cp - command copy (ex cp original.txt duplicate.txt)

mv - move files (ex mw path\file.txt backup)

rm - remove files (ex rm path\file.txt

cat - view inside files (ex cat file.txt)

head - view firet -n rows (ex heda file.csv)

man - manual coomand (man head)

history - show the request history 

grep - seasrch string or word or... in file (grep word file.txt)

> - redirect optut in one file into another (head file.txt > file_2.txt)

| - use the output of the command on the left as the input to the command on the right (head file.txt | tail -n 3)

  
 **read the file with cut: cut -d , -f numbers of columns**
 
 Tables for wc:
\begin{tabular}{|l|l|l|}
\hline Параметр & Длинньй вариант & Значение \\
\hline$-c$ & --bytes & Отобразить размер объекта в байтах \\
\hline$-m$ & --count & Показать количесто символов в объекте \\
\hline-1 & -- ines & Вьвести количество строк в объекте \\
\hline$-w$ & -words & Отобразить количество слов в объекте \\
\hline
\end{tabular}

**Note : click tab - input the first match; click x2 tab - view all optionts;**

Flags : 
1. -n : numbers of count (head -n 100 ...)
2. -R : all files view (ls -R)
3. -f : fields (cut -f)
4. -d:  delimiter (cut -f, ..., -d)

### Spark 
Spark is a distributed computing platform. It achieves efficiency by distributing data and computation across a cluster of computers.

parts of the Spark:
- cluster manager
- one or more nodes
- API 
