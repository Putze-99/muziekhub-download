# BooBeats

Een muziekbibliotheek voor DJ's die op je eigen computer draait. Geen
account, geen cloud, geen abonnement.

> BooBeats heette eerst **MuziekHub**. De bestanden die je downloadt heten
> daarom nog `MuziekHub-…`; het is dezelfde app.

- **Overzicht:** al je muziek op één plek, met BPM, toonsoort (Camelot),
  genres, labels en sterren.
- **Opschonen:** dubbele nummers vinden, slechte kwaliteit verbeteren en
  nep-lossless herkennen.
- **Playlists en sets:** playlists maken, harmonische mix-tips krijgen en een
  set laten samenstellen.
- **Rekordbox:** een koppeling die je bibliotheek naar Rekordbox stuurt.
- **Binnenhalen:** muziek ophalen van je eigen mappen en USB-sticks, of met je
  eigen account van YouTube, SoundCloud en Soulseek.
- **Volglijsten:** de Spotify-lijst van iemand anders volgen. Je luistert
  eerst het fragment en houdt alleen wat je goed vindt.

## Downloaden

Ga naar **[de nieuwste versie](../../releases/latest)** en kies het bestand
voor jouw computer:

| Jouw computer | Bestand |
|---|---|
| Windows | `MuziekHub-…-setup.exe` |
| Mac met Apple Silicon (M1, M2, M3, M4) | `MuziekHub-…-mac.dmg` |
| Mac met Intel (grofweg 2020 en eerder) | `MuziekHub-…-mac-intel.dmg` |

Liever geen installer op Windows? `MuziekHub-…-windows.zip` werkt ook, zie
hieronder. Staat de versie voor jouw computer er nog niet bij, dan komt die
eraan. De bestanden `…-update.zip` en `update.json` heb je niet nodig; die
gebruikt BooBeats zelf om bij te werken.

Je hoeft niets anders te installeren: Python, ffmpeg en de rest zitten al in
de download.

## Installeren op Windows

1. Download `MuziekHub-…-setup.exe` en dubbelklik erop. Zegt je browser dat
   het bestand *"niet vaak wordt gedownload"*, kies dan **Behouden** (in Edge
   onder de drie puntjes **⋯**, daarna **Meer weergeven** en
   **Toch behouden**).
2. Zegt Windows *"Windows heeft uw pc beveiligd"*? Klik op
   **Meer informatie** en daarna op **Toch uitvoeren**.
3. Klik op **Volgende** en **Installeren**. Een beheerderswachtwoord is niet
   nodig. BooBeats en BooBeats Mini komen in het Startmenu en, als je dat
   aanvinkt, op je bureaublad.

Verwijderen gaat via **Instellingen > Apps**. Je bibliotheek, playlists en
downloads blijven dan staan.

**Liever de zip?** Rechtsklik hem, kies **Alles uitpakken** naar een vaste
plek (niet de map Downloads) en dubbelklik in de uitgepakte map op
**MuziekHub.vbs**. Laat Verkenner de extensies niet zien, neem dan de
"MuziekHub" met het blauwe pictogram.

## Installeren op de Mac

Op de Mac heet de app voorlopig nog **MuziekHub**.

1. Dubbelklik op het `.dmg`-bestand en sleep **MuziekHub** op **Programma's**.
2. Dubbelklik MuziekHub. Zegt je Mac dat de ontwikkelaar niet gecontroleerd
   kan worden, ga dan naar **Systeeminstellingen > Privacy en beveiliging**,
   scroll naar beneden en klik op **Toch openen**.
3. Zegt je Mac *"MuziekHub is beschadigd"*? Open Terminal en plak:

   ```
   xattr -dr com.apple.quarantine /Applications/MuziekHub.app
   ```

## Waarom die waarschuwing?

BooBeats is niet digitaal ondertekend. Zo'n handtekening kost per jaar geld
bij Microsoft en Apple. Daarom vragen je browser en je computer één keer of je
het vertrouwt.

## De eerste keer

Een welkomstscherm helpt je in drie stappen: je muziekmap kiezen, Soulseek
koppelen (mag je overslaan) en de koppeling met Rekordbox. Daarna bepaalt
BooBeats op de achtergrond van elk nummer de BPM en de toonsoort.

## Bijwerken

Je hoeft hier niet terug te komen. BooBeats kijkt zelf één keer per dag of er
een nieuwe versie is. Dan staat onderin de zijbalk **↑ Versie … is er**, en
één klik werkt hem bij. Je muziek, bibliotheek en instellingen blijven
gewoon staan. Had je nog MuziekHub, dan word je met dezelfde knop BooBeats.

## Goed om te weten

BooBeats levert zelf geen muziek en heeft geen eigen account. Het is
gereedschap voor je eigen bibliotheek, net als Rekordbox. Wat je ermee
downloadt, is je eigen verantwoordelijkheid. Spotify-links gebruik je alleen
om een tracklijst over te nemen.

In de download zitten ffmpeg, yt-dlp en slskd, met hun licenties in de map
`LICENTIES`.
