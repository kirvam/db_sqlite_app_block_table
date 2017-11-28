 This is the db_sqlite_app_block app.

 The goal is to create a lightweight Perl based information/note gather app which uses parent child relationships and which is Docker ready (portable).

 EntryA
  |___NoteA
  |___NoteB
 
 EntryB
  |___NoteA
  |___NoteB

 Howto run it:
 
 sudo /usr/local/bin/plackup bin/app.psgi --port 5003 --host 0.0.0.0



   -Paul
# db_sqlite_app_block_table
