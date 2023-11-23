# Installatieinstructies

Controleer of cowsay geinstalleerd is:

``` shell
#!/bin/bash
if command -v cowsay >/dev/null 2>&1; then
    echo "cowsay is al geïnstalleerd!"
else
    echo "cowsay is nog niet geïnstalleerd!"
fi
```

Installeer het programma 'cowsay' met het commmando:

``` shell
sudo apt update && sudo apt install cowsay
```

Kopieer het bestand arjen.cow naar de folder '/usr/share/cowsay/cows' met het commando:

``` shell
sudo cp arjen.cow /usr/share/cowsay/cows/
```

Test of de installatie geslaagd is met het commando: 

``` shell
cowsay -f arjen "Installatie geslaagd!"'
```
