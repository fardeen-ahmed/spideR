# spideR
spideR is a subdomain enumeration tool that uses different data sources to derive a complete list of subdomains for a given domain. (Made by Fardeen Ahmed in learning phase.)

## Sources
Additional spideR queries following sources to derive a list of subdomains:

- Search Engines:
  - Google
  - Bing
  - Yahoo
- Virus Total

## Install

Before all, very first set aws with Access_Key & Secret_Key by the command :-

$ aws configure

## Then do the following additions :- 

- Directly copy the binary from the `binaries` subdirectory
- Compile it using the following:

## Pipelining with other tools (right now, httpx is only supported. With new updates, it will add major tools)

- One can pipe this tool with httpx by -> $ spideR -d example.com | httpx -title -tech-detect -follow-redirects 
 (This will give more information about WAF such as Cloudfront, and redirections.

#### Future sources

Additional spideR is an active project, the following sources will be added in coming releases, working on these new functionalities:
- crt.sh
- DNS bruteforcer
- webpage crawling
