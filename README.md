# spideR
spideR is a subdomain enumeration tool that uses different data sources to derive a complete exhaustive list of subdomains for a given domain. (Made by Fardeen Ahmed in learning phase.)

## Sources
Additional subdigger queries following sources to derive a list of subdomains:

- Search Engines:
  - Google
  - Bing
  - Yahoo
- Virus Total

## Install

- Directly copy the binary from the `binaries` subdirectory
- Compile it using the following:

## Pipelining 

- One can pipe this tool with httpx by -> $ spideR -d example.com | httpx -title -tech-detect -follow-redirects (This will give more information about WAF, and redirections.


#### Future sources

Additinoal subdigger is an active project, the following sources will be added in coming releases, working on these new functionalities:
- crt.sh
- DNS bruteforcer
- webpage crawling
