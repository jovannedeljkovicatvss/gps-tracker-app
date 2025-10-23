# 📄 Specifikacija projekta: Lovački GPS Tracker

## 🧭 Opis projekta

Android aplikacija za praćenje GPS uređaja u realnom vremenu, namenjena za lovačke aktivnosti, terensko kretanje i bezbednosno praćenje. Korisnik može da vidi trenutnu lokaciju uređaja, istoriju kretanja, postavi geo-fence zone i dobija upozorenja.

---

## 🎯 Ciljevi

- Omogućiti korisnicima da prate GPS uređaje putem mobilne aplikacije
- Prikazati lokaciju na mapi sa markerima i statusima
- Implementirati osnovne bezbednosne funkcije (geo-fence, alarm)
- Omogućiti pregled istorije kretanja

---

## 🧩 Funkcionalnosti

### 1. Autentifikacija
- Logovanje korisnika putem Firebase Auth
- Osnovna zaštita pristupa aplikaciji

### 2. Prikaz mape
- Google Maps SDK
- Marker za svaki uređaj
- Klik na marker prikazuje detalje

### 3. Real-time praćenje
- Automatsko osvežavanje lokacije svakih X sekundi
- Prikaz brzine, signala, baterije

### 4. Istorija kretanja
- Pregled rute po danima
- Prikaz vremenskih tačaka

### 5. Geo-fence
- Definisanje zone na mapi
- Upozorenje ako uređaj napusti zonu

### 6. Upravljanje uređajima
- Dodavanje uređaja putem ID-a
- Lista svih povezanih uređaja

---

## 🏗️ Tehnologije

| Sloj         | Tehnologija                         |
|--------------|-------------------------------------|
| Frontend     | Android Studio + Jetpack Compose    |
| Mapa         | Google Maps SDK                     |
| Backend      | Traccar server (open-source)        |
| Baza         | PostgreSQL / Firebase Realtime DB   |
| Autentifikacija | Firebase Auth                    |
| Komunikacija | TCP/UDP protokol (GT06, TK103…)     |

---

## 📅 Plan razvoja

| Faza                         | Rok              |
|-----------------------------|------------------|
| Specifikacija i dizajn      | 1. nedelja       |
| Osnovna struktura aplikacije| 2. nedelja       |
| Integracija mape            | 3. nedelja       |
| Backend komunikacija        | 4–5. nedelja     |
| Geo-fence i istorija        | 6. nedelja       |
| Testiranje i dorada         | 7. nedelja       |
| Dokumentacija i prezentacija| 8. nedelja       |

---

## 📁 Struktura projekta
