MIT AKVARIUM V2 – OPDATERING TIL GITHUB

1. TAG BACKUP AF DIN NUVÆRENDE OneDrive/Apps/Akvarier/Akvarier.xlsx.
2. Upload index.html, manifest.webmanifest, sw.js, icon.svg, icon-192.png og icon-512.png til roden af GitHub-repository bsstaal/Akvarier. Erstat eksisterende index.html.
3. Vent på GitHub Pages, og genindlæs https://bsstaal.github.io/Akvarier/ med Ctrl+F5. Hvis den gamle app vises, ryd webstedets cache/service worker én gang.
4. Log ind med Microsoft. Den eksisterende Excel-fil læses som før.
5. Registrér en testmåling eller vedligeholdelse. Ved første vellykkede gemning tilføjer programmet arkene Vandværdier og Vedligeholdelse og kolonnen BilledeData i Akvarier.
6. Test med et billede, og kontrollér at ændringerne også vises i Excel.
7. Installér på mobil: Chrome Android > menu > Installer app; Safari iPhone > Del > Føj til hjemmeskærm.

VIGTIGT:
- Erstat IKKE din eksisterende Akvarier.xlsx med en tom skabelon.
- Programmet bruger Files.ReadWrite.AppFolder og Microsoft-login som hidtil.
- Billeder komprimeres og gemmes som data i Excel (ikke som separate OneDrive-filer). Store billeder kan gøre Excel langsom. Programmet begrænser den samlede XLSX-størrelse til 3,5 MB.
- Microsoft-login og synkronisering kræver internet. PWA giver installation og mulighed for at åbne en cachet skal, ikke offline-redigering.
- OneDrive Excel gemmes som en hel fil. Hold den lukket i Excel, og undgå samtidige redigeringer.
- Ikke live-testet mod din konto; test på backup og behold originalfilen.
