# notes

Process your notes

optional arguments:

###  -h, --help            
show this help message and exit
  
###  -ls, --list
List all notes. You can use modifier -i to list notes  
with specific importance
                        
###  -a, --add
Add note.
  
###  -e EDIT, --edit EDIT
Edit note with given index
  
###  -r REMOVE, --remove REMOVE
Removing note with given ingex. Be careful! After
removing a note, indexes of notes with bigger indexes will decrease
                        
###  -n NOTE, --note NOTE
Note text. Note can contain whatever you want BUT
should contain only ONE line, newline symbols will be
replaced by space
                        
###  -k KEY, --key KEY
Key. Key should be just few words. Commas, dots and
other special symbols will be removed, all letters
will be lowercased
                        
###  -s SEARCH, --search SEARCH
Search for notes with given or similar key
                        
###  -i IMPORTANCE, --importance IMPORTANCE
Importance of note [0-9], 0 - most important, 9 - not
important at all (why you add it then?). If you
searching then it will be shown all results with that
or greater(with smaller number) importance. If you
adding new note, than by default it's importance is
zero
                        
###  -p PATH, --path PATH
Path to note storage. Default path is ./notes_database
