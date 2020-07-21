# ZABBIX PROJECT
Instrukcja i sprawozdanie z instalacji oraz konfiguracji zabbixa. Dodatkowym zadaniem projektu jest uruchomienie działającej usługi podobnej do [Network Weathermap](https://www.network-weathermap.com). System monitorujący postaram się postawić na maszynie z CentOS'em oraz obserwować maszyny z CentOS/Debian/Kali.
`
## Research ogólny 
- [Zabbix eng wikipedia](https://en.wikipedia.org/wiki/Zabbix), [Zabbix rus wikipedia](https://ru.wikipedia.org/wiki/Zabbix) - ogólne informacje o usłudze. Ponieważ 30 czerwca skończyło się wsparcie dla wersji 4.x będę instalował usługę w wersji 5.x.
- [Zabbix wiki](https://zabbix.org/wiki/Main_Page) - zabbixowa wiki - tutaj są informacje odnośnie instalacji i w sumie wszystkiego co może nas interesować
- [Strona zabbixa](https://www.zabbix.com) - tutaj są linki do wszystkich ważnych stron
- [Poradnik do instalacji zabbixa](https://www.howtoforge.com/tutorial/centos-zabbix-system-monitoring/) - z tego korzystam do instalacji oraz konfiguracji

## Instalacja
1. Tutaj powinna pojawić się instalacja oraz konfiguracja serwera httpd, natomiast to już zrobiłem instalując munina, zatem pomijam ten krok
2. Instalacja PHP
   a. Dociągnięcie potrzebnych paczek php 
      ```bash dnf install php-cli php-common php-devel php-pear php-gd php-mbstring php-mysqlnd php-xml php-bcmath``` 

