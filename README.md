# Sistem za prodaju i validaciju ulaznica za sportske događaje 🎟️


Ovaj projekat predstavlja Java klijentsko–serverski sistem za prodaju i kontrolu ulaznica za sportske događaje.
Sistem simulira realan proces prodaje karata, generisanja ulaznica i njihove validacije pomoću QR kodova.
Aplikacija je podeljena na više komponenti kako bi se postigla bolja organizacija i razdvajanje odgovornosti.
<br>&nbsp;

## 🧩 Struktura projekta

Ovaj repozitorijum služi kao centralno mesto za dokumentaciju i pregled celog sistema.
Projekat se sastoji iz sledećih delova: 
<br>&nbsp;

🔹 Klijentska aplikacija

Desktop aplikacija (Swing) koja omogućava rad operatera – upravljanje događajima i prodaju ulaznica.

👉 https://github.com/mm20200041/Prodaja-Karata-Klijent
<br>&nbsp;
 
🔹 Serverska aplikacija

Zadužena za poslovnu logiku, rad sa bazom podataka i komunikaciju sa klijentom.

👉 https://github.com/mm20200041/Prodaja-Karata-Server
<br>&nbsp;

🔹 Zajednički modul

Sadrži zajedničke klase (modeli, komunikacioni objekti, pomoćne klase) koje koriste i klijent i server.

👉 https://github.com/mm20200041/Prodaja-Karata-Zajednicki
<br>&nbsp;

## 🚀 Funkcionalnosti

- Evidencija utakmica, hala, sektora, redova i sedišta

- Automatsko generisanje ulaznica za svaku utakmicu

- Kreiranje računa sa više stavki

- Generisanje PDF ulaznica sa QR kodovima

- Slanje ulaznica kupcu putem email-a

- Validacija ulaznica pomoću QR koda

- Sprečavanje ponovne upotrebe već iskorišćenih karata
<br>&nbsp;

## 🛠 Tehnologije

- Java

- Swing (GUI)

- JDBC

- MySQL

- HTTP (klijent–server komunikacija)

- Generisanje PDF dokumenata

- Obrada QR kodova
<br>&nbsp;

## 🧱 Arhitektura

Sistem je zasnovan na klijentsko–serverskoj arhitekturi:

- Klijent omogućava interakciju sa korisnikom (GUI)
  
- Server obrađuje poslovnu logiku i rad sa bazom

- Zajednički modul obezbeđuje razmenu podataka između komponenti

- Validacija obezbeđuje proveru ulaznica i sprečava zloupotrebu
<br>&nbsp;

## 🔮 Moguća unapređenja

- Uvođenje REST API-ja umesto trenutne komunikacije

- Web aplikacija umesto desktop (Swing) rešenja

- Integracija sa platnim sistemima

- Mobilna aplikacija za skeniranje ulaznica

- Autentifikacija korisnika i različite uloge
