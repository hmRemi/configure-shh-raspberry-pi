# Hvordan aktivere SSH på Raspberry Pi 4
---
## Aktivere SSH via Desktop:
1. Klikk på Raspberry Pi-ikonet på skrivebordet.
2. Naviger til **Innstillinger**, og klikk deretter på **Raspberry Pi-konfigurasjon**.
3. Klikk på fanen **Grensesnitt** og velg **Aktiver** i alternativene for SSH.
4. Klikk **OK**.

## Aktivere SHH via terminalen:
- Åpne Raspberry Pi-terminalen.
- Skriv inn kommandoen: `sudo raspi-config`
- Bruk piltastene for å navigere til **Grensesnittalternativer**. Trykk **Enter**.
- Gå til **SSH**, og trykk **Enter**.
- Når du blir bedt om det, velg **"Ja"**.
- Velg **Enter** for å bekrefte, og deretter klikker du på **Fullfør** for å avslutte raspi-config.
- Lukk terminalvinduet.
---
## Aktivere SSH via installasjon av Raspberry Pi for første gang:
1. Naviger til **Avanserte alternativer** i Raspberry Pi Imager.
2. Klikk på avmerkingsboksen ved siden av **Aktiver SSH**.
3. Klikk **Lagre**, og skriv operativsystemet til lagringsenheten du velger.
