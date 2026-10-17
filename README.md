# decky-store

Catalogo custom per Decky Loader (Steam Deck).

URL da inserire in Decky Loader → Settings → Canale del negozio → Personalizzato:

```
https://raw.githubusercontent.com/loddi-o/decky-store/main/store.json
```

Ogni plugin resta nel proprio repository (codice + release con lo zip); questo repo contiene solo `store.json`, il catalogo che elenca i plugin disponibili e punta agli asset delle rispettive release.

## Aggiungere un nuovo plugin

Aggiungere una voce all'array in `store.json` con lo stesso schema usato per "WoL Deck", puntando alla release (asset zip) del repo del plugin.

I plugin senza un repository proprio (per ora Claude Code) tengono lo zip in `plugins/` di questo repo.
