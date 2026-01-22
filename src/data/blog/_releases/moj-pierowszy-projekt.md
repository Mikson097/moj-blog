---
author: Mikołaj Liszewski
pubDatetime: 2026-01-22T15:22:00Z
title: Mój pierwszy projekt IT
postSlug: moj-pierwszy-projekt
featured: true
draft: false
tags:
  - projekty
  - nauka
description: Tu znajdzie sie krótki instruktarz jak zainstalowac Proxmoxa
---

## Cześć!
<b>Krok 1 ISO </b><br>
Dobra to zacznijmy przygotuj sobie pendrive tak z 8GB i wjedz na stronke https://www.proxmox.com/en/downloads i pobierz sobie wersję która cię interesuje.<br> 
<b>Krok 2 Boot pendirve</b> <br>
Jak już masz to zrób sobie bootowalnego pena ja preferuje użyc rufusa ale jesli masz jakąś inna apke to okej.<br>
<b>Krok 3 Sprzęt</b> <br>
Podłącz pena do urządzenia na którym chcesz mieć proxmoxa. Wejdź do biosu używając kalwiszy(F2,Del,F10) i ustaw żeby bootwoało z pendrive na 1 miejscu <br>
<b>Krok 4 Instalacja</b> <br>
Jak już sie odpali to powinno się wam wyświetlic coś takiego polecam wybierzcie sobie to co chcecie na początek zalecam graphical 
![alt text](image.png)<br>
Polecam zaakceptowac Eula
![alt text](image-1.png)<br>
Następnie wybieracie dysk który wam odpowiada jak macie jeden pamiętajcie, że wszystkie dane z partycji utworzonej zostaną usunięte klikacie next
![alt text](image-2.png)<br>
Następnie wyświetli sie location and time zone to polecam wpisac Poland w miejce Country ale tak to next <br>
Nasępny krok to ustawienie Hasła administratora polecam zrobić jakieś mocne hasło bo jest to ważne. <br>
Jesli chodzi o pole email polecam stworzyć nowy bo on bedzie po wysyłanie alertów typu że coś nie działa w systemie.<br>
Teraz się wyświetli konfiguracja sieciowa wybierzcie odpowieni interfejs który was interesuje<br>
Jeśli chodzi o Hostname nazwijcie go sobie jak checei ale polecam jakis srv-głowny.pve czy cos takiego<br>
Jeśli chodzi o address IP no to ustawiacie według własnego widzimise jak macie automatyczny dhcp to raczej powinno wam go przydzielic więc klikamy next<br>
![alt text](image-3.png)<br>
No i wyświetla wam sie podsumowanie jeśli wszystko się zgadza to klikamy install 


