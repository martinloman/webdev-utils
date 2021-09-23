# Browser-sync

Ett verktyg för att automatiskt ladda om sidan i webbläsaren varje gång du sparar den.

## Installation

Du installerar browser-sync med hjälp av ett verktyg som heter NPM. Det kan du ladda ned och installera från [nodejs.org](https://nodejs.org/en/download/).

Installation görs genom att köra följande kommando i kommandotolken (Command promt)

```
npm install -g browser-sync
```

## Starta browser-sync

För att starta en webbserver sin automatisk uppdateras så kör du följande kommando i kommandotolken. **_I den katalog dina filer ligger._**

```
browser-sync start -s -f . --no-notify
```

När du kör kommandot så kommer din standardwebbläsare öppnas. Adressen kommer vara något i stil med http://localhost:3000, där visas din sida.
