# Provider-Services-Manager

Ovaj projekat predstavlja .NET biblioteku i grafičku aplikaciju dizajniranu za Internet i TV provajdere. Aplikacija omogućava provajderima efikasno upravljanje paketima usluga koje njihovi klijenti koriste, čuvajući podatke o korisnicima i paketima u bazi podataka.

## Funkcionalnosti:
- **CRUD funkcije za Client-a**
- **CRUD funkcije za Packet**
- **Aktivacija i deaktivacija paketa za klijenta**
- **Izlistivanje paketa odvojenim po grupama**
- **Prikaz paketa na koje je klijent prijavljen**
  
## Konfiguracija:
Čitanje podataka iz config.txt fajla za konfiguraciju provajdera
Omogućava više provajdera da koriste istu aplikaciju sa različitim bazama i imenima
## Package install
- **Open (View -> Other Windows -> Package Manager Console)**
- **Execute in terminal : Install-Package Microsoft.Data.Sqlite -ProjectName ProjectName ('UI' and 'Library')**
- **Execute in terminal : Install-Package System.Data.Sqlite -ProjectName ProjectName ('UI' and 'Library')**

## Podrška za Različite Tipove Baza:
Biblioteka podržava konekciju sa bar 2 različita tipa baze (npr. SQLite i MySQL)

## Korišćeni Softverski Paterni:
- **Singleton: Za obezbeđivanje jedinstvene instance baze.**
- **Builder: Za kreiranje kompleksnih objekata paketa.**
- **Factory Method: Za instanciranje odgovarajućih tipova baza podataka.**
- **Decorator: Za dodavanje dodatnih informacija o paketima.**
- **Observer: Za praćenje promena aktiviranih paketa.**
- **Facade: Za pojednostavljenje pristupa bazama podataka.**
- **Memento: Za čuvanje stanja aplikacije.**
- **Repository: Za pristup podacima o klijentima i paketima.**

## Grafički Korisnički Interfejs (GUI):
- **Prikaz naziva provajdera**
- **Prikaz liste svih klijenata**
- **Prikaz liste svih paketa razdvojenih po tipu**
- **Dodavanje novog klijenta**
- **Brisanje vec postojec klijenta**
- **Aktivacija i deaktivaciaj paketa klijentima**

## Zaključak:
Ovaj projekat kombinuje efikasno upravljanje podacima i korisnički interfejs kako bi pružio provajderima intuitivan način za manipulaciju paketima usluga. Korišćeni softverski paterni dodatno doprinose skalabilnosti, održivosti i čitljivosti koda. Sveukupno, ova aplikacija pruža snažan temelj za efikasno vođenje poslovanja Internet i TV provajdera.

## Pokretanje:
Pokretanje se vrsi direktno iz samo editora, ili vec iz izbildane aplikacije, potrebno je samo u config.txt, za konekcioni string postavi path svoje database-a.
