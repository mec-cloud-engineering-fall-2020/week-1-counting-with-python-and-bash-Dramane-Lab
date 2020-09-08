[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=3092351&assignment_repo_type=AssignmentRepo)
# Week 1: Counting with Python and Bash

## Part one

Write a function in `count.py` that prints the total number of lines in all the files in the `/files` directory. For example, if there are 3 files with 10 lines each, your function should print `30`. Your function should still work even if I add or take away files from the directory.

A useful resource: https://realpython.com/read-write-files-python/

Extension #1 (optional): Show additional statistics besides the total number of files, such as the average number of lines per file, or the average number of words per line.

Extension #2 (optional): Write another function, `count_unique`, that only adds up the total number of lines from unique files. For example, if there are three files, A, B, and C, which each have 10 lines, and A and C are the exact same, then you should ignore A, and print 20.

## Part two

Write an explanation in `WRITEUP.md` of how to use Bash to count up the total number of lines in all the files in `/files` (same as you did in part one), and give an example of the command you would run to produce the same result.

The tools you'll need: https://en.wikipedia.org/wiki/Cat_(Unix), https://en.wikipedia.org/wiki/Pipeline_(Unix), https://en.wikipedia.org/wiki/Wc_(Unix)

## Part three

Write your thoughts in `WRITEUP.md` about whether you think Python or Bash is better for this task. What advantages and disadvantages do each of them have for this?
