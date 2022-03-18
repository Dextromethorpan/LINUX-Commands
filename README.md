# LINUX-Commands
Linux Commands that I mostly use


Find Command

To find a file when we know the file path

find /filepath filename 

To find a file that ends at .zwr in the filepath

find /filepath -name "*.zwr"

To find a file that ends at .m and start with g

find / -name '*.m' -name 'g*'

To find a folder when we know the folder path

find /folderpath -type d -name "foldername"

-----------------------------------------------------------------------

Cat & Sed Command

To show a file content

cat filename

To show a file content and the number of lines

cat -n filename

To show a special text in a file 

cat filename | grep 'text'

To show specific range(5-8)

sed -n 5,8p filename

-----------------------------------------------------------------------

Grep Command

To find a word in a list of files

grep -n "word" *


To find a word in a file 

grep word filename


To find a word in multiple files 

grep word filename1 filename2 filename3


To find a word as uppercase and lowercase in multiple files

grep -i "word" *


To find a word in subdirectories

grep -r "word" *


To find a word in a list of matching files

grep -l "word" *


To count the number of matches 

grep -c "word" *

-----------------------------------------------------------------------








