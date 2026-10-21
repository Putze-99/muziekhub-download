# MuziekHub

Een muziekbibliotheek voor DJ's die op je eigen computer draait. Geen
account, geen cloud, geen abonnement.

- **Overzicht:** al je muziek op één plek, met BPM, toonsoort (Camelot),
  genres, labels en sterren.
- **Opschonen:** dubbele nummers vinden, slechte kwaliteit verbeteren en
  nep-lossless herkennen.
- **Playlists en sets:** playlists maken, harmonische mix-tips krijgen en een
  set laten samenstellen.
- **Rekordbox:** een koppeling die je bibliotheek naar Rekordbox stuurt.
- **Binnenhalen:** muziek ophalen van je eigen mappen en USB-sticks, of met je
  eigen account van YouTube, SoundCloud en Soulseek.

## Downloaden

Ga naar **[de nieuwste versie](../../releases/latest)** en kies het bestand
voor jouw computer:

| Jouw computer | Bestand |
|---|---|
| Windows | `MuziekHub-…-windows.zip` |
| Mac met Apple Silicon (M1, M2, M3, M4) | `MuziekHub-…-mac.dmg` |
| Mac met Intel (grofweg 2020 en eerder) | `MuziekHub-…-mac-intel.dmg` |

Staat de versie voor jouw computer er nog niet bij, dan komt die eraan. De
bestanden `…-update.zip` en `update.json` heb je niet nodig; die gebruikt
MuziekHub zelf om bij te werken.

Je hoeft niets anders te installeren: Python, ffmpeg en de rest zitten al in
de download.

## Installeren op Windows

1. Rechtsklik de zip en kies **Alles uitpakken**. Kies een vaste plek,
   bijvoorbeeld `C:\MuziekHub` of je map Documenten, en niet de map Downloads.
2. Dubbelklik in de uitgepakte map op **MuziekHub.vbs**. Laat Verkenner de
   extensies niet zien, dan staan er twee bestanden die "MuziekHub" heten;
   neem die met het blauwe pictogram.
3. Zegt Windows *"Windows heeft uw pc beveiligd"*? Klik op
   **Meer informatie** en daarna op **Toch uitvoeren**.

## Installeren op de Mac

1. Dubbelklik op het `.dmg`-bestand en sleep **MuziekHub** op **Programma's**.
2. Dubbelklik MuziekHub. Zegt je Mac dat de ontwikkelaar niet gecontroleerd
   kan worden, ga dan naar **Systeeminstellingen > Privacy en beveiliging**,
   scroll naar beneden en klik op **Toch openen**.
3. Zegt je Mac *"MuziekHub is beschadigd"*? Open Terminal en plak:

   ```
   xattr -dr com.apple.quarantine /Applications/MuziekHub.app
   ```

## Waarom die waarschuwing?

MuziekHub is niet digitaal ondertekend. Zo'n handtekening kost per jaar geld
bij Microsoft en Apple. Daarom vraagt je computer één keer of je het
vertrouwt.

## De eerste keer

Een welkomstscherm helpt je in drie stappen: je muziekmap kiezen, Soulseek
koppelen (mag je overslaan) en de koppeling met Rekordbox. Daarna bepaalt
MuziekHub op de achtergrond van elk nummer de BPM en de toonsoort.

## Bijwerken

Je hoeft hier niet terug te komen. MuziekHub kijkt zelf één keer per dag of er
een nieuwe versie is. Dan staat onderin de zijbalk **↑ Versie … is er**, en
één klik werkt hem bij. Je muziek, bibliotheek en instellingen blijven
gewoon staan.

## Goed om te weten

MuziekHub levert zelf geen muziek en heeft geen eigen account. Het is
gereedschap voor je eigen bibliotheek, net als Rekordbox. Wat je ermee
downloadt, is je eigen verantwoordelijkheid. Spotify-links gebruik je alleen
om een tracklijst over te nemen.

In de download zitten ffmpeg, yt-dlp en slskd, met hun licenties in de map
`LICENTIES`.
