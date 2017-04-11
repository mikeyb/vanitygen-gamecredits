##  Requirements

Debian/Ubuntu: `sudo apt install openssl libssl-dev libpcre++-dev git build-essential`

##  Install

git clone https://github.com/mikeyb/vanitygen-gamecredits.git
cd vanitygen-gamecredits/
make

##  Usage

###  Generate Single Key
`./vanitygen -G 'G'`

```
Difficulty: 1
Pattern: G                                                                     
Address: GZGkrCGNQ2ELdcH6tKYw7PQihzFZzvP6wE
Privkey: 6amGpwEMATwKKEPXF3UW7acCbCwctiaWNVdSjY1hYj86eBYQ3YQ
```

###  Generate Vanity Key
`./vanitygen -G 'Game'`

```
Difficulty: 78508
Pattern: Game                                                                  
Address: GamecsTR4PoNVtcH6BenNhc5xXCvHQm59g
Privkey: 6bRFEeaXuauCP6aXK9AHvhcKW6ZxLDJu3fJBPFrK2vSAzXNSBL2
```
