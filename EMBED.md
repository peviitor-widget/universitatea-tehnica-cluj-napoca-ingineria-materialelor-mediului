# Cod de integrare — widget joburi

**Facultate:** Facultatea de Ingineria Materialelor si a Mediului, Universitatea Tehnica Cluj-Napoca

**Pagina widgetului:** https://peviitor-widget.github.io/universitatea-tehnica-cluj-napoca-ingineria-materialelor-mediului/

Copiază codul de mai jos în pagina site-ului facultății, acolo unde vrei să apară widgetul:

```html
<iframe
  src="https://peviitor-widget.github.io/universitatea-tehnica-cluj-napoca-ingineria-materialelor-mediului/#/widget?title=Joburi+pentru+studenti&color=%234f46e5"
  width="100%"
  height="650px"
  style="border: none; background: transparent;"
></iframe>
```

## Parametri opționali

| Parametru | Descriere | Exemplu |
|-----------|-----------|---------|
| `title` | Titlul afișat în widget | `Joburi pentru studenți` |
| `color` | Culoarea temei, hex (`#` se scrie `%23`) | `%234f46e5` |

Fără parametri, widgetul folosește valorile din `conf/widget.json`.

---

Fișier generat automat de workflow-ul *1. Configurează widgetul facultății*. Nu îl edita manual — modificările se pierd la următoarea rulare.
