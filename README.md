# Iptables-firewall-script
Petit script Iptables permettant de tout bloquer et de n'ouvrir que les ports par défaut.

➡ Comment l'utiliser ?
Il vous suffit de réaliser un chmod+x pare-feu.sh pour rendre le script exécutable, puis un simple ./pare-feu.sh et le tour est joué.

➡ Quel(s) port(s) ouvre-t-il ?
Les classiques, donc SSH, DNS, FTP, HTTP, HTTPS, POP, SMTP, IMAP... à vous de rajouter/supprimer ce dont vous avez envie !

➡ Est-il compatible avec X distribution GNU/Linux ?
Ce script a uniquement été testé sur Debian, de la 7 à 9 (Wheezy à Stretch), mais il devrait être portable sans trop de difficultés sur d'autres (il suffit d'installer iptables).
