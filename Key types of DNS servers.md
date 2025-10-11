The DNS Lookup Process

- **Browser Cache Check:** 
    
    When you enter a domain name, your browser first checks its own cache and the operating system's hosts file for a stored IP address. 
    

- **Recursive Resolver Request:** 
    
    If the IP isn't found locally, your computer sends a request to its configured DNS recursive resolver, often provided by your Internet Service Provider (ISP) or a third-party service. 
    

- **Root Name Server:** 
    
    The recursive resolver first contacts a root name server, which tells it where to find the servers responsible for the domain's top-level domain (e.g., .com, .org). 
    

- **Top-Level Domain (TLD) Name Server:** 
    
    The resolver then queries the appropriate TLD name server, which directs it to the authoritative name servers for the specific domain. 
    

- **Authoritative Name Server:** 
    
    Finally, the resolver contacts the authoritative name server, the final source of truth for that domain's IP address. 
    

- **IP Address Return:** 
    
    The authoritative name server returns the IP address to the recursive resolver, which then sends it back to your computer's operating system and browser. 
    

- **Caching:** 
    
    The IP address is then cached locally and by the recursive resolver for future use, speeding up subsequent requests.