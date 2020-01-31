    _____                        _   __          ___ _     _                   _           
    |  __ \                      (_)  \ \        / (_) |   | |                 | |          
    | |  | | ___  _ __ ___   __ _ _ _ _\ \  /\  / / _| | __| | ___ __ _ _ __ __| | ___ _ __ 
    | |  | |/ _ \| '_ ` _ \ / _` | | '_ \ \/  \/ / | | |/ _` |/ __/ _` | '__/ _` |/ _ \ '__|
    | |__| | (_) | | | | | | (_| | | | | \  /\  /  | | | (_| | (_| (_| | | | (_| |  __/ |   
    |_____/ \___/|_| |_| |_|\__,_|_|_| |_|\/  \/   |_|_|\__,_|\___\__,_|_|  \__,_|\___|_|  
    A commandline tool to wildcard domain registrations against the RIPE database (com/net only)
    @littl3field
    

    
     
  ## Optional arguments in order:
  ```
  -h, --help    show this help message and exit
  
  50 results displayed per query
  
  -s SINGLE     Single domain to check, example = -s google (default: None)
  -f FILENAME   File to be checked with one domain per line (default: None)
  -w WHITELIST  Set a file containing whitelisted domains (default: None)
  -o OUTPUT     Set a file to output too (default: None)
  ```
  
  # Example single domain argument 
  ```
  python WhoIsWildcarder.py -s google -w WhiteListFile.txt 
  ```
  
  # Example file (list of domains) argument 
  ```
  python WhoIsWildcarder.py -f example.txt -w WhiteListFile.txt -o CustomOutput.log
  ``` 
  Example output:
  ```
	GOOGLE--ANALYTICS.COM
	GOOGLE--FLIGHT.COM
	GOOGLE--FLIGHTS.COM
	GOOGLE--IT.COM
	GOOGLE--SEARCH.COM
	GOOGLE--YAHOO.COM
	GOOGLE-0.COM
	GOOGLE-0.NET
	GOOGLE-01.COM
	GOOGLE-010.COM
	GOOGLE-021.COM
	GOOGLE-1.COM
	GOOGLE-1.NET
	GOOGLE-10.COM
	GOOGLE-10.NET
	GOOGLE-100.COM
	GOOGLE-100.NET
	GOOGLE-1004.COM
	GOOGLE-123.COM
	GOOGLE-163.COM
	GOOGLE-1ST.COM
	GOOGLE-2.COM
	GOOGLE-2.NET
	GOOGLE-21.COM
	GOOGLE-3.COM
	GOOGLE-3.NET
	GOOGLE-360.COM
	GOOGLE-365.COM
	GOOGLE-3CX.COM
	GOOGLE-3G.COM
	GOOGLE-3G.NET
	GOOGLE-4-JOBS.COM
	GOOGLE-4RWC.COM
  ```
  
  # TODO:
  
  - Lots.
