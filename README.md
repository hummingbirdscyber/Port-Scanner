# Port-Scanner
This tool is a basic port scanner that written with python to learn understand the basic some Python libraries and Networking concepts.
        
    
    $python3 PortScanner.py -h
    usage: PortScanner.py [-h] [-i IP | -d DOMAIN] [-p [PORT [PORT ...]]]
                          [-t THREAD]
    
    optional arguments:
      -h, --help            show this help message and exit
      -i IP, --ip IP        Target's ip
      -d DOMAIN, --domain DOMAIN
                            Target's domain name
      -p [PORT [PORT ...]], --port [PORT [PORT ...]]
                            Target ports' number interval
      -t THREAD, --thread THREAD
                            How many threads do you want to use?
    
    
    Examples:
    
    $python3 PortScanner.py -d scanme.nmap.org -p 1 25 -t 4
    [+] Port--> 22
    
    $python3 PortScanner.py -i 127.0.0.1 -p 1 1000 -t 4
    [+] Port--> 443
    [+] Port--> 631
    [+] Port--> 902
