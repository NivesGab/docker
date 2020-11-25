Instalacija in konfiguracija je izvedena s pomočjo Dockerja.

Z datoteko wordpress_docker-compose.yml namestimo spletno stran Wordpress, podatkovno bazo MariaDB, traefik in portainer.
Z datoteko jitsi_docker-compose.yml namestimo storitev Jitsi Meet.

Dodala sem portainer za nadzor in opravljanje kontejnerjev, traefic za pregled reverse proxy-ja.
Zaradi generiranja certifikatov sem dodala tudi svojo domeno za katero traefik reverse proxy generira certifikate in ureja preusmeritev iz porta 80 na 443.
Domeno posodablja Duckdns.

Jitsi in wordpress sta dosegljiva na domenah:
-http://edusrv47a.t-2.com/
-http://edusrv47b.t-2.com/

https povezavi:
-https://wordpress1.nivest2.duckdns.org/
-https://meet.nivest2.duckdns.org/

