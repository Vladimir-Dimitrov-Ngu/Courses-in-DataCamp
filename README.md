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


**Create shell script**
nano create.sh
for i in files; do cat -d , -f 2 $i | grep -v 'name column' | sort | uniq -n | sort -r 
bash create.sh > file.txt

### Spark 
Spark is a distributed computing platform. It achieves efficiency by distributing data and computation across a cluster of computers.

parts of the Spark:
- cluster manager
- one or more nodes
- API 


### Data Structure and algorithm Python

##### Linked lists

Linked lists: sequence of data connected through links

Every element names node and contain of 2 parts: first part - data, second part - pointer (to the next node). Last link point to null

##### Stack 
Princip: Last-in-First-out (LIFO) - last inserted item will be the first item to be removed

Popping from the stack: remove the last item from the stack

Peeking from the stack: read the last item from the stack 

Stacks real uses:
1. Undo functionality 
2. Symbol checker 
3. Function calls

Stacks implemetation using singly linked lists
