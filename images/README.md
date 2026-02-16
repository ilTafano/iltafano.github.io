# Cartella Immagini

Inserisci qui le immagini per articoli, pubblicazioni e contenuti in evidenza.

## Formato Consigliato

- **Formato**: JPG, PNG o WebP
- **Dimensioni consigliate**:
  - Card nelle liste: 800x600px
  - Dettaglio articolo: 1200x800px
- **Peso**: cerca di mantenere le immagini sotto i 500KB per prestazioni migliori

## Come Usare

1. Carica l'immagine in questa cartella
2. Nel file `js/data.js`, aggiungi il percorso nel campo `image`:

```javascript
{
  id: "5",
  title: "Mio articolo",
  // ... altri campi
  image: "/images/nome-file.jpg"  // ← Percorso immagine
}
```

## Esempio

Se carichi un file chiamato `mercato.jpg` in questa cartella, il percorso sarà:

```javascript
image: "/images/mercato.jpg";
```

**Nota**: Il campo `image` è opzionale. Se lasciato vuoto (`image: ""`), verrà mostrato un placeholder grigio.
