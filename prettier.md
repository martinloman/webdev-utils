# Prettier - Code formatter

Prettier är ett verktyg som formaterar HTML och CSS på ett bra sätt. Det gör din kod lätt att läsa och därmed lättare att upptäcka fel/misstag i.

Prettier installeras som Extension i VS Code. Sök efter "prettier".

Hemsidan finns här: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

## Format on save

Prettier fungerar allra bäst om du ser till att dina filer formateras automatiskt varje gång du sparar filen.

För att göra det i VS Code klickar på kugghjulet längst ned till vänster i fönstret och väljer _Settings_. I Settings-fliken som öppnas söker du på `format` och kryssar i kryssrutan för _Format on save_. Klart! Du kan nu stänga settings-fliken.

### Felsökning

Formateras inte din kod när du sparar? Det finns två troliga fel och åtgärder.

1. Du har inte Prettier som standard-formaterare. Åtgärd: höger-klicka i en HTML- eller CSS-fil, välj Format Document, välj Prettier.
2. Du har syntax-fel i din fil som hindrar Prettier från att formatera filen. Åtgärd: Fixa syntaxfelen. Verktyg som HTMLHint och stylelint är bra för att hitta syntax-problem i HTML respektive CSS.
