SKY HUNTERS 0.3 — INSTALLEREN

1. Upload alleen index.html naar de ROOT van je bestaande GitHub-repository sky-hunters. Vervang het bestaande index.html.
2. Wacht op GitHub Pages en open https://richardvg033.github.io/sky-hunters/
3. Tik GPS inschakelen en Live ophalen.
4. Als Safari 'Load failed' toont, heb je waarschijnlijk een proxy nodig.

OPTIONELE PROXY (iets technischer):
1. Maak een gratis Cloudflare-account aan op dash.cloudflare.com.
2. Ga naar Workers & Pages > Create > Worker.
3. Open Edit code en vervang de standaardcode door de inhoud van worker.js. Deploy.
4. Kopieer de URL van je Worker (https://...workers.dev).
5. In Sky Hunters open je 'Live verbinding instellen', plak de Worker-URL en tik Bewaar verbinding.
6. Tik opnieuw op Live ophalen.

Let op: gratis diensten kennen gebruikslimieten. De vliegtuigdatabron kan verzoeken blokkeren of de voorwaarden wijzigen. Test eerst met kleine aantallen; publiceer geen sleutels in GitHub. De Worker stuurt alleen locatiecoordinaten door naar de vliegtuigdatabron. Dit is een prototype, geen gegarandeerde live service.

Je verzameling van 0.2 is niet automatisch overgezet omdat de opslagstructuur van de eerdere versie onbekend is. Maak zo nodig een backup voordat je vervangt.
