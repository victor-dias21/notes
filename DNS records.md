Common DNS record types

DNS records are instructions that authoritative servers use to provide information about a domain. 

- **A record:** Maps a domain name (like `example.com`) to an IPv4 address.
- **AAAA record:** Maps a domain name to an IPv6 address.
- **CNAME record:** An alias that points one domain or subdomain to another domain name instead of an IP address. This is often used for subdomains like `www`.
- **MX record:** Specifies the mail servers responsible for accepting email messages on behalf of a domain.
- **NS record:** Indicates which DNS servers are authoritative for a domain.
- **TXT record:** Holds text notes used for email security (SPF, DKIM, DMARC) and domain verification.
- **PTR record:** Used for a reverse DNS lookup, which maps an IP address back to a domain name.