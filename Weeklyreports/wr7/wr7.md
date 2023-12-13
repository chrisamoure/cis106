---
Chris Corona
cis 106
Week report 7
---

## Question 1

 | Commands | What It Does                                                | Syntax                                    | Example                                                                                  |
 | -------- | ----------------------------------------------------------- | ----------------------------------------- | ---------------------------------------------------------------------------------------- |
 | cat      | display contents of a file                                  | cat + option + file        | `cat todo.lst` and `cat ~/Documents/todo.lst`                                            |
 | tac      | display the content of a file in reverse order              | tac + option + file         | `tac todo.md` and `tac ~/Downloads/todo.md`                                              |
 | head     | displays the top N number of lines of a file                | head + option + file                  | `head ~/Documents/Book/dracula.txt` and `head -5 ~/Documents/Book/dracula.txt`           |
 | tail     | displays the last N number of lines of a file               | tail + option + file                   | `tail ~/Documents/Book/dracula.txt` and `tail 5 ~/Documents/Book/dracula.txt`            |
 | cut      | extracts section of each line of file and displays          | cut + option + file                    | `cut -d ':' -f1 /etc/passwd` and ` cut -d ':' -f1,7 /etc/passwd`                         |
 | paste    | joins files horizontally in columns                         | paste + option + file                  | `paste users.lst ip_address.lst` and `paste -d ':' users1.lst ip_addresses.lst`          |
 | sort     | sorts file                                                  | sort + option + file                 | `sort users.lst` and `sort -r users.txt`                                                 |
 | wc       | prints the number of lines, characters, and bytes in a file | wc + option + file                    | `wc -m users.txt` and `wc -l users.txt`                                                  |
 | tr       | translates or deletes characters from standard output       | Standard output l tr + option + set + set | `cat file.txt l tr '.' ','` and `cat file.py l tr -s "[:space:]" ' '`                    |
 | diff     | compares files and displays the differences between them    | diff + option + file1 + file2             | `diff cars.csv cars-backup.csv` and `diff -y cars.csv cars-backup.csv`                   |
 | grep     | search text in given file                                   | grep + option + file + file(s) | `grep 'dracula' ~/Documents/dracula.txt` and `grep -i 'dracula' ~/Documents/dracula.txt` |