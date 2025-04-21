---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes enum. Denna enum uppräknar möjliga lägen för inbäddning av filer som refereras i HTML. Den gör det möjligt att kontrollera om refererade filer kommer att inbäddas i huvud-HTML-filen eller genereras som separata binära enheter.
type: docs
weight: 5710
url: /sv/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

Denna enum uppräknar möjliga lägen för inbäddning av filer som refereras i HTML. Den gör det möjligt att kontrollera om refererade filer (HTML, typsnitt, bilder, CSS) kommer att inbäddas i huvud-HTML-filen eller genereras som separata binära enheter.

```csharp
public enum PartsEmbeddingModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Tvingar inbäddning av alla refererade filer (CSS, bilder, typsnitt) i den genererade HTML-markupen (dvs. i HTML själv). Denna metod genererar en HTML-fil, men den totala storleken på utdata blir större (eftersom Base64-kodning av binärer används) och inte alla webbläsare (särskilt äldre) bearbetar framgångsrikt binärer inbäddade i HTML. Men det gör det möjligt att få HTML som innehåller hela resultatet, utan några ytterligare filer. |
| EmbedCssOnly | `1` | Tvingar att separera alla refererade filer utom CSS (bilder och typsnitt). Dvs. CSS kommer att inbäddas i den resulterande HTML, och alla andra refererade filer (bilder och typsnitt) kommer att behandlas som externa delar. Det genererar HTML som är lämplig för ett brett utbud av webbläsare. |
| NoEmbedding | `2` | Tvingar att separera refererade filer (CSS, bilder, typsnitt). Denna metod genererar en uppsättning filer, men den totala storleken på utdata blir mindre (eftersom ingen Base64-kodning av binärer används). Denna metod genererar också HTML som är lämplig för ett brett utbud av webbläsare. |

### Se Även

* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)