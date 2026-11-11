# NASP – Heš tabele

Projekat iz predmeta **Napredni algoritmi i strukture podataka** (ETF Sarajevo, 2026/27).

## Tema

Upoređivanje brzine i efikasnosti različitih heš algoritama nad većim skupovima podataka.

Cilj je implementirati tri heš tabele u C++ i eksperimentalno uporediti njihove performanse:
vrijeme umetanja, vrijeme pretrage i zauzeće memorije, za skupove od 10³ do 10⁷ ključeva.

## Algoritmi

- **Universal Chaining**: rješava kolizije povezanim listama, uz univerzalnu heš funkciju
- **FKS Perfect Hashing**: dvonivojska tabela bez kolizija, pretraga O(1) u najgorem slučaju, za statičke skupove
- **Cuckoo Hashing**: dvije tabele i dvije heš funkcije, pretraga provjerava najviše dva mjesta

## Autori

- Emir Agović
- Ernad Žuga
- Nermin Obućina
