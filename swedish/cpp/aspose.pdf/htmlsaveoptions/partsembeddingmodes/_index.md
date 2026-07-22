---
title: "Aspose::Pdf::HtmlSaveOptions::PartsEmbeddingModes enum"
linktitle: "PartsEmbeddingModes"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::PartsEmbeddingModes enum. Detta enum listar möjliga lägen för inbäddning av filer som refereras i HTML. Det gör det möjligt att styra om refererade filer (HTML, teckensnitt, bilder, CSS-filer) ska bäddas in i huvud‑HTML‑filen eller genereras som separata binära enheter i C++."
type: docs
weight: 5800
url: /sv/cpp/aspose.pdf/htmlsaveoptions/partsembeddingmodes/
---
## PartsEmbeddingModes enum


Denna enum enumererar möjliga lägen för inbäddning av filer som refereras i HTML. Den låter dig kontrollera om refererade filer (HTML, teckensnitt, bilder, CSS-filer) kommer att bäddas in i huvud‑HTML‑filen eller genereras som separata binära enheter.

```cpp
enum class PartsEmbeddingModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| EmbedAllIntoHtml | 0 | Tvingar inbäddning av alla refererade filer (Css, Images, Fonts) i den genererade HTML‑markupen (dvs. i själva HTML‑filen). Detta tillvägagångssätt genererar en HTML‑fil, men den totala storleken på utdata blir större (eftersom Base64‑kodning av binärer används) och inte alla webbläsare (särskilt äldre) kan framgångsrikt bearbeta binärer som är inbäddade i HTML. Men det möjliggör att få HTML som innehåller hela resultatet utan några ytterligare filer. |
| EmbedCssOnly | 1 | Tvingar att separera alla refererade filer förutom CSS (bilder och teckensnitt). Det vill säga, CSS kommer att bäddas in i resultat‑HTML, medan alla andra refererade filer (bilder och teckensnitt) behandlas som externa delar. Det genererar HTML som är lämplig för ett brett urval av webbläsare. |
| NoEmbedding | 2 | Tvingar att separera refererade filer (Css, Images, Fonts). Detta tillvägagångssätt genererar en uppsättning filer, men den totala storleken på utdata blir mindre (eftersom ingen Base64‑kodning av binärer används). Sådant tillvägagångssätt genererar också HTML som är lämplig för ett brett urval av webbläsare. |

## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
