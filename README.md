Sistem za prodaju i validaciju ulaznica za sportske događaje 🎟️


Ovaj projekat predstavlja Java klijentsko–serverski sistem za prodaju i kontrolu ulaznica za sportske događaje.
Sistem simulira realan proces prodaje karata, generisanja ulaznica i njihove validacije pomoću QR kodova.

Aplikacija je podeljena na više komponenti kako bi se postigla bolja organizacija i razdvajanje odgovornosti.

🧩 Struktura projekta

Ovaj repozitorijum služi kao centralno mesto za dokumentaciju i pregled celog sistema.
Projekat se sastoji iz sledećih delova:

🔹 Klijentska aplikacija

Desktop aplikacija (Swing) koja omogućava rad operatera – upravljanje događajima i prodaju ulaznica.

👉 https://github.com/USERNAME/client-repo-link


🔹 Serverska aplikacija

Zadužena za poslovnu logiku, rad sa bazom podataka i komunikaciju sa klijentom.

👉 https://github.com/USERNAME/server-repo-link


🔹 Zajednički modul

Sadrži zajedničke klase (modeli, komunikacioni objekti, pomoćne klase) koje koriste i klijent i server.

👉 https://github.com/USERNAME/common-repo-link


🚀 Funkcionalnosti

evidencija utakmica, hala, sektora, redova i sedišta

automatsko generisanje ulaznica za svaku utakmicu

kreiranje računa sa više stavki

generisanje PDF ulaznica sa QR kodovima

slanje ulaznica kupcu putem email-a

validacija ulaznica pomoću QR koda

sprečavanje ponovne upotrebe već iskorišćenih karata


🛠 Tehnologije

Java

Swing (GUI)

JDBC

MySQL

HTTP (klijent–server komunikacija)

generisanje PDF dokumenata

obrada QR kodova


🧱 Arhitektura

Sistem je zasnovan na klijentsko–serverskoj arhitekturi:

klijent omogućava interakciju sa korisnikom (GUI)
  
server obrađuje poslovnu logiku i rad sa bazom

zajednički modul obezbeđuje razmenu podataka između komponenti

validacija obezbeđuje proveru ulaznica i sprečava zloupotrebu


🔮 Moguća unapređenja

uvođenje REST API-ja umesto trenutne komunikacije

web aplikacija umesto desktop (Swing) rešenja

integracija sa platnim sistemima

mobilna aplikacija za skeniranje ulaznica

autentifikacija korisnika i različite uloge
