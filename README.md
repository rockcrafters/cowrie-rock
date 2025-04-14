# cowrie-rock
Cowrie is a medium to high interaction SSH and Telnet honeypot designed to 
log brute force attacks and the shell interaction performed by the 
attacker. In medium interaction mode (shell) it emulates a UNIX system in 
Python, in high interaction mode (proxy) it functions as an SSH and telnet 
proxy to observe attacker behavior to another system.

See: https://github.com/cowrie/cowrie

## Example

Execute the honey-pot SSH instance on port 2222: 
```
docker run --rm -it -p 2222:2222 cowrie:latest
```
<!-- ## TODO -->
