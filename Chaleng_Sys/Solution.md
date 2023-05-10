# SOLUTION LEVEL ROOT ME 


# FTP Authentification :
## Etape:
### 1 - Telecharger le sujet .
### 2 - Ouvrez le fichier sur Wirashark (Nom du dossier : ch1.pcap) .
### 3 - Rechecher sur le bar de recherche ==> telnet .
### 4 - Faire click droite sur le flux TCP , follow , TCP stream  ==> solution de nos challenge .
![subject-1](solution1.png)


# TELNET Authentification :
## Etape:
### 1 - Telecharger le sujet .
### 2 - Ouvrez le fichier sur Wirashark (Nom du dossier : ch2.pcap) .
### 3 - Rechecher sur le bar de recherche ==> telnet .
### 4 - Faire click droite sur le flux TCP , follow , TCP stream  ==> solution de nos challenge .
![subject-1](solution2.png)


# Twitter Authentification:
## Etape:
### 1 - Telecharger le sujet .
![subject-1](hex.png)
### 2 - Decode les Hex dans le fichier et convertir en String.
![subject-1](hexToString.png)
### 3 - Decode le mot de passe qui a de base 64  .
![subject-1](solution3.png)

# ETHERNET Trame :
## Etape:
### 1 - Telecharger le sujet .
### 2 - Ouvrez le fichier sur Wirashark (Nom du dossier : ch3.pcap) .
### 3 - Faire click  sur "Hypertext Transfer Protocol" puis "Authorization"  ==> solution de nos challenge .
![subject-1](solution4.png)

# BLUETOOTH - Fichier inconnu (à faire même si cela n'a pas été fait lors de la séance de ce jour) :
## Etape:
### 1 - Telecharger le sujet .
### 2 - Ouvrez le fichier sur Wirashark .
### 3 - Click sur Wireless puis Bluetooth Devices.
![subject-1](searchCode.png)
### Encript le hash SHA1 de la concaténation de l’adresse MAC (en majuscules) et du nom du téléphone .
![subject-1](solution5.png)

# Les challengs réuissie :
![subject-1](clalleng.png)