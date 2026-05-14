# Autokooli juhtimissüsteem (Autokool Management System)

## Projekti kirjeldus
See rakendus on loodud autokooli igapäevaste protsesside automatiseerimiseks. Süsteem muudab suhtluse administratsiooni, sõiduõpetajate ja õpilaste vahel kiiremaks ja läbipaistvamaks, võimaldades hallata tunniplaane, jälgida õppekäiku ja hoida korras vajalikku dokumentatsiooni.

**Sihtrühmad:**
* **Õpilased:** sõidutundide broneerimiseks ja teooria progressi jälgimiseks.
* **Õpetajad:** oma töögraafiku ja õpilaste nimekirja haldamiseks.
* **Administraatorid:** üldise õppeprotsessi kontrollimiseks ja andmebaasi haldamiseks.

## Meeskond
* **Vitali Kolesnikov** 
* **Emil Munassypov** 
* **Aleksandr Gritsenko**

## Tehnoloogiad
* **Programmeerimiskeel:** Kotlin (Android)
* **Andmebaas:** Firebase
* **Arhitektuur:** MVVM (Model-View-ViewModel) 

## Nõuded süsteemile

### Funktsionaalsed nõuded:
1.  **Kasutajate haldus:** Erinevad õigused ja vaated administraatorile, õpetajale ja õpilasele.
2.  **Sõidutundide broneerimine:** Õpilane saab valida vaba aja õpetaja graafikus ja selle broneerida.
3.  **Õpingute jälgimine:** Kuvatakse läbitud sõidutundide arv ja sooritatud kontrolltööd.
4.  **Profiili muutmine:** Võimalus muuta kontaktandmeid ja parooli.
5.  **Teavitused:** teavitused lähenevate sõidutundide või tunniplaani muudatuste kohta.

### Mittefunktsionaalsed nõuded:
1.  **Turvalisus:** Kasutajaandmete krüpteerimine ja turvaline sisselogimine.
2.  **Jõudlus:** Rakenduse liides peab reageerima viivitusteta 
3.  **Ühilduvus:** Toetatud kõigi tänapäevaste nutitelefonide poolt

## UML Kasutusjuhtude diagramm (Use Case Diagram)
<img width="809" height="672" alt="image" src="https://github.com/user-attachments/assets/739ad140-32e0-4bc4-b5ff-e052154f313d" />


## Tööplaan (Sprindid)
1.  **Sprint 1: Planeerimine.** Nõuete analüüs, UML-diagrammide ja UI-kavandite koostamine.
2.  **Sprint 2: Baasarendus.** Repositooriumi seadistamine, Firebase'i integreerimine ja sisselogimissüsteemi loomine.
3.  **Sprint 3: Põhifunktsionaalsus.** Broneerimissüsteemi ja isikliku kabineti loogika väljatöötamine.
4.  **Sprint 4: Testimine ja dokumentatsioon.** Vigade parandus, testide läbiviimine ja README lõplik vormistamine.
