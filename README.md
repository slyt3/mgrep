# mgrep
 Creating a grep clone that can do simple substring searching within files. It auto-recurse into subdirectories.
 
* Using goroutines to search through the files for a substring match
* Displays matches to the terminal as they are found
* Displays the line number, file path, and complete line containing the match
* Recurses into any subdirectories looking for matches
* Using any synchronization method to ensure that all files
  are searched, and all results are displayed before the program
  terminates.

* Program invocation follow the pattern:
    mgrep search_string search_dir
