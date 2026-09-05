# Aardgas FLEX vs VAST

## ▶ [Open de rekentool](https://forsskieken.github.io/gasvergelijker/)

**Niets downloaden, niets installeren.** Klik op de link en de rekentool opent in
uw browser, ook op een telefoon.

Vergelijk uw aardgascontract bij meerdere leveranciers — variabel (FLEX) tegen
vast — over de komende twaalf maanden, met netkosten, taksen en vaste
vergoedingen inbegrepen.

![De rekentool met de standaardcijfers](docs/screenshot.png)

## Zo gebruikt u hem

1. Vul uw **jaarverbruik** in kWh in. Dat staat op uw jaarafrekening.
2. Zet de **TTF-schuifregelaar** op de koers van vandaag, in euro per MWh. De
   pagina linkt naar [Yahoo Finance](https://finance.yahoo.com/quote/TTF%3DF/) en
   naar de beurs [ICE](https://www.theice.com/products/27996665/Dutch-TTF-Gas-Futures).
3. Kies een **prijsscenario** voor het komende jaar — de drie tabbladen.
4. Vul per leverancier de vaste vergoeding en de energieprijs in. De jaarprijs
   rekent mee terwijl u typt; de goedkoopste rij krijgt een label.

## Zelf een kopie bewaren

Rechtsklik op de link hierboven en kies opslaan, of download `index.html` van
deze pagina. Het bestand werkt vanaf uw schijf; enkel de grafieken en het
lettertype komen van het internet.

## Wat het berekent

| Onderdeel | Detail |
|---|---|
| FLEX-energieprijs | `(0,1 × TTF-maandgemiddelde + 1,021) × 1,06`, in ct/kWh incl. 6 % btw |
| Breekpunt | De TTF-koers waaronder FLEX goedkoper is dan het vaste contract |
| Netkosten | Fluvius Antwerpen T2 (> 5 000 kWh/jaar), vaste term plus per kWh |
| Transport | Fluxys, per kWh |
| Accijnzen | 0,9782 ct/kWh tot 12 000 kWh, 1,0681 ct/kWh daarboven |
| Maandprofiel | Jaarverbruik gespreid over een typisch Belgisch stookprofiel |

## Lees dit voor u een cijfer gelooft

- **De tarieven zijn een momentopname van maart 2026** en de scenario's zijn
  geschreven rond de markt van dat moment. Toets elk cijfer aan de actuele
  tariefkaart voor u iets beslist.
- Alleen de tarieven van één leverancier zijn ingevuld; de rest blijft nul tot u
  ze zelf invult.
- De TTF die u online vindt is de dagkoers, terwijl de formule met het
  maandgemiddelde rekent. Goed genoeg voor een raming, niet exact.
- Ramingen, geen aanbod. Geen financieel advies.
- Er verlaat niets uw browser: geen upload, geen server, niets bewaard.
