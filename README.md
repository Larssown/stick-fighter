# Stick Fighter

Ett enkelt fightingspel med streckgubbar för två spelare online, direkt i webbläsaren.

## Spela

1. Öppna spelet och klicka **Skapa match**. Du får en kod med fyra tecken.
2. Skicka koden (eller länken) till din motståndare. Den skriver in koden och klickar **Gå med**.
3. Båda trycker **slag** när de är redo. Först till två vunna ronder vinner.

## Kontroller

| | Tangent |
|---|---|
| Gå | A / D eller ← → |
| Hoppa | W eller ↑ |
| Blockera | S eller ↓ |
| Slag | F eller K |
| Spark | G eller L |

## Teknik

Allt ligger i `index.html`. Webbläsarna ansluter direkt till varandra med WebRTC via [PeerJS](https://peerjs.com).
Den som skapar matchen kör spelet och skickar läget till motståndaren varje bildruta.
Ingen egen server behövs, så spelet kan ligga på GitHub Pages.
