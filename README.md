    _____                        _   __          ___ _     _                   _           
    |  __ \                      (_)  \ \        / (_) |   | |                 | |          
    | |  | | ___  _ __ ___   __ _ _ _ _\ \  /\  / / _| | __| | ___ __ _ _ __ __| | ___ _ __ 
    | |  | |/ _ \| '_ ` _ \ / _` | | '_ \ \/  \/ / | | |/ _` |/ __/ _` | '__/ _` |/ _ \ '__|
    | |__| | (_) | | | | | | (_| | | | | \  /\  /  | | | (_| | (_| (_| | | | (_| |  __/ |   
    |_____/ \___/|_| |_| |_|\__,_|_|_| |_|\/  \/   |_|_|\__,_|\___\__,_|_|  \__,_|\___|_|  
    A commandline tool to wildcard domain registrations against the whois database (com/net only)
    @littl3field
     
  ## Optional arguments in order:
  
  -h, --help    show this help message and exit
  -s SINGLE     Single domain to check, example = -s google (default: None)
  -f FILENAME   File to be checked with one domain per line (default: None)
  -w WHITELIST  Set a file containing whitelisted domains (default: None)
  -o OUTPUT     Set a file to output too (default: None)
  
  # Example single domain argument 
  ```
  python WhoIsWildcarder.py -s google -w WhiteListFile.txt 
  ```
  
  # Example file (list of domains) argument 
  ```
  python WhoIsWildcarder.py -f example.txt -w WhiteListFile.txt -o CustomOutput.log
  ``` 
  # TODO:
  
  - Lots.
