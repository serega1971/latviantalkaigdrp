# Privātuma politika — LatvianTalk AI

**Versija:** 1.1
**Spēkā no:** 2026-09-27
**Pārzinis:** LatvianTalk AI komanda (kontakts: sergey.krasnikov@gmail.com)

Šī politika apraksta, kādus personas datus apstrādā mobilā lietotne LatvianTalk AI un kādēļ. Lietojot lietotni, jūs apstiprināt, ka esat iepazinies ar šo politiku.

## 1. Apstrādātie dati un mērķi

| Datu kategorija | Mērķis | Juridiskais pamats | Glabāšana |
|---|---|---|---|
| **Balss straume** (mikrofona ieraksts sarunas laikā) | Sarunas vadīšana ar AI skolotāju | Piekrišana (VDAR 6.1.a) | Mēs neglabājam. Tiek pārraidīts tiešsaistē uz OpenAI apstrādei. |
| **Sarunas teksts** (nodarbības atšifrējums) | Kļūdu analīze un vārdu krājuma profila papildināšana pēc nodarbības | Piekrišana | Mēs neglabājam. Pēc nodarbības tiek nosūtīts uz OpenAI caur mūsu Cloud Function; saglabājas tikai analīzes rezultāts — kļūdu kategorijas un vārdi. |
| **Konts**: lietotāja identifikators, bet, pieslēdzoties ar Google, arī e-pasts un profila vārds | Vēstures piesaiste jums un datu nodalīšana starp lietotājiem | Piekrišana | Firebase Authentication, līdz konta dzēšanai. Anonīmi pieslēdzoties — tikai identifikators. |
| **Kļūdu vēsture** (kategorija, apraksts, jūsu frāze un tās labojums) | Skolotāja pielāgošana jūsu vājajām vietām | Piekrišana | Ierīcē (Room datu bāze) un jūsu kontā Cloud Firestore (ES), līdz jūs tos dzēšat. |
| **Vārdu krājuma profils** (tēmas un vārdi, ko esat lietojis) | Uzdevumu izvēle pēc jūsu leksikas | Piekrišana | Ierīcē un Cloud Firestore (ES), līdz jūs tos dzēšat. |
| **Sesiju metadati** (sarunas ID, sākuma un beigu laiks, kļūdu skaits) | Statistikas attēlošana | Piekrišana | Ierīcē un Cloud Firestore (ES). |
| **Iestatījumi** (valoda, fonta izmērs, dienas mērķis, nodarbību sērija, atgādinājumi) | Lietotnes darbība | Piekrišana | Tikai ierīcē. |

Mēs **neapkopojam**: atrašanās vietu, kontaktus, ierīces identifikatorus reklāmai, analītikas izsekotājus. Lietotne nepievieno analītikas vai kļūdu ziņojumu servisus.

## 2. Apakšprocesori

- **OpenAI, L.L.C.** (ASV) — sniedz AI skolotāja balss servisu (Realtime API) un nodarbības atšifrējuma analīzi. Balss straume tiek pārraidīta tiešsaistē, sarunas teksts — pēc nodarbības. OpenAI glabāšanas politika: skat. https://openai.com/policies/privacy-policy.
- **Google Ireland Limited / Google LLC** — Firebase Authentication (konts), Cloud Firestore (kļūdu vēsture, vārdu krājuma profils, sesiju metadati), Cloud Functions un Cloud Logging. Firestore atrodas ES multireģionā `eur3`, funkcijas — `europe-north1` (Somija). Firebase Authentication dati var tikt apstrādāti ASV.

Datu pārsūtīšanas uz ASV pamats: datu apstrādes vienošanās (DPA) ar OpenAI un ar Google, kā arī standarta līguma klauzulas.

## 3. Jūsu tiesības (VDAR III nodaļa)

- **Piekļuve un kopija** — kļūdu vēsture un vārdu krājuma profils ir redzami "Statistika" ekrānā lietotnē.
- **Dzēšana** — "Notīrīt" poga "Statistika" ekrānā dzēš visu kļūdu vēsturi gan ierīcē, gan mākonī; vārdu krājuma profila vārdus tur pat var dzēst pa vienam. Poga "Dzēst kontu" tajā pašā ekrānā izdzēš visu uzreiz: kļūdu vēsturi, vārdu krājuma profilu, sesiju metadatus, iestatījumus un pašu kontu — gan ierīcē, gan mākonī. To nevar atsaukt.
- **Piekrišanas atsaukšana** — "Dzēst kontu" izdzēš datus un vienlaikus atsauc piekrišanu. Vienkārša lietotnes atinstalēšana dzēš tikai datus ierīcē, mākonī tie paliek.
- **Sūdzība** — Datu valsts inspekcijai (https://www.dvi.gov.lv).

## 4. Vecuma ierobežojums

Lietotne paredzēta lietotājiem no **16 gadu** vecuma (VDAR 8. pants par bērnu piekrišanu digitālajiem pakalpojumiem).

## 5. Drošība

Balss straume un visi pieprasījumi serveriem tiek pārraidīti pa šifrētu savienojumu (TLS). Dati ierīcē glabājas lietotnes privātajā direktorijā un ir pieejami tikai šai lietotnei. Cloud Firestore piekļuves noteikumi ļauj lasīt un rakstīt datus tikai konta īpašniekam.

Ņemiet vērā: lietotnē ir ieslēgta standarta Android dublēšana, tāpēc tās dati ierīcē var tikt kopēti uz jūsu Google Drive. To var izslēgt Android iestatījumos.

## 6. Politikas izmaiņas

Politikas versija tiek paaugstināta, ja mainās datu apstrāde. Pie versijas paaugstinājuma jūs tiksiet aicināts piekrist no jauna.

## 7. Kontakts

Jautājumi: sergey.krasnikov@gmail.com
