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



Sukuriamas grep klonas, galintis atlikti paprastą poeilutės paiešką failuose. Jis automatiškai pasikartoja į pakatalogius.

Gorutinų naudojimas ieškant poeilutės atitikties failuose

Rodo atitikmenis su terminalu, kai jie bus rasti

Rodo eilutės numerį, failo kelią ir visą eilutę, kurioje yra atitiktis

Pasikartoja į bet kokius pakatalogius ir ieško atitikmenų

Naudojant bet kokį sinchronizavimo metodą, siekiant užtikrinti, kad būtų ieškoma visų failų ir visi rezultatai būtų rodomi prieš pasibaigiant programai.

Programos iškvietimas seka šabloną: mgrep search_string search_dir
