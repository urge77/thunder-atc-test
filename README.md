# Thunder ATC (testversjon)

> 🔒 **Nedlastingen er passordbeskyttet.**
> Du må ha fått passordet av Thunder2977 for å pakke den ut.
> Har du ikke passordet, er det ingen vits i å laste den ned.
>
> 🔒 **The download is password protected.**
> You need a password from Thunder2977 to extract it. Without it, the file cannot be opened.

AI-flygeleder for Microsoft Flight Simulator, med talegjenkjenning, SimBrief og GSX Pro.

## Last ned

Gå til **[Releases](../../releases/latest)** og last ned `Thunder.ATC.test.7z`.

## Slik kommer du i gang

1. Pakk ut `.7z`-fila **lokalt** på PC-en (f.eks. på skrivebordet) med [7-Zip](https://www.7-zip.org/) eller WinRAR, og skriv inn passordet.
2. Dobbeltklikk **«Start Thunder ATC.exe»** i mappa `thunder-atc`.
   Sier Windows «Windows beskyttet PC-en»: trykk «Mer info» → «Kjør likevel».
   Det er normalt: programmet er ikke signert med et kjøpt sertifikat, så Windows kjenner ikke utgiveren. Bare første gang.
   *Vil du slippe varselet:* høyreklikk den nedlastede `.7z`-fila **før** du pakker ut → Egenskaper → huk av «Fjern blokkering» → OK.
3. Første gang lastes talegjenkjenning (ca. 145 MB) ned automatisk i bakgrunnen. Ikke lukk programmet imens.
4. Trykk **«Innstillinger»**, skriv inn SimBrief-brukernavnet ditt og trykk «Lagre».
5. Trykk **«Hent fra SimBrief»**, start MSFS og sett deg i flyet.
6. Hold **høyre CTRL** og snakk med ATC (tast eller flyspak-knapp kan endres under Innstillinger).

Mer hjelp står i `LES MEG FØRST.txt` i mappa.

Python trengs ikke. Avinstallere: slett mappa `thunder-atc`.

## Krav

- Windows 10/11
- Microsoft Flight Simulator 2024 eller 2020
- Mikrofon
- GSX Pro (valgfritt)

## Problemer?

Send fila `thunder-atc\atc\thunder_atc_logg.txt` til Thunder2977.

---

## English

1. Download `Thunder.ATC.test.7z` from **[Releases](../../releases/latest)** and extract it locally with the password you received.
2. Run **«Start Thunder ATC.exe»** (SmartScreen: «More info» → «Run anyway» – normal, the program isn't signed with a paid certificate; or right-click the `.7z` before extracting → Properties → «Unblock»).
3. Speech recognition (~145 MB) downloads automatically on first start.
4. Open «Innstillinger» (Settings), enter your SimBrief username, click «Lagre» (Save).
5. Click «Hent fra SimBrief», start MSFS, hold **right CTRL** to talk.

Uninstall: delete the `thunder-atc` folder. Problems? Send `atc\thunder_atc_logg.txt` to Thunder2977.
