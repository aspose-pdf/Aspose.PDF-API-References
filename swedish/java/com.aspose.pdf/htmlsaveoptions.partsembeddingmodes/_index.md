---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna enum listar möjliga lägen för inbäddning av filer som refereras i HTML. Den tillåter att kontrollera om refererade filer (HTML, teckensnitt, bilder, CSS) kommer att bäddas in i huvudfilen."
type: docs
weight: 2130
url: /sv/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

Denna enum enumererar möjliga lägen för inbäddning av filer som refereras i HTML. Den möjliggör att styra om refererade filer (HTML, teckensnitt, bilder, CSS) ska inbäddas i huvud‑HTML‑filen eller genereras som separata binära enheter

## Fält

| Fält | Beskrivning |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Tvingar inbäddning av alla refererade filer (Css, Bilder, Teckensnitt) i den genererade HTML-markupen (dvs. i själva HTML). Detta tillvägagångssätt skapar en HTML-fil, men den totala storleken på utdata blir större (eftersom Base64-kodning av binärer används) och inte alla webbläsare (särskilt äldre) kan framgångsrikt bearbeta binärer som är inbäddade i HTML. Men det möjliggör att få HTML som innehåller hela resultatet utan några extra filer. |
| [EmbedCssOnly](#EmbedCssOnly) | Tvingar att separera alla refererade filer förutom CSS (bilder och teckensnitt). Det vill säga, CSS kommer att bäddas in i resultat-HTML, och alla andra refererade filer (bilder och teckensnitt) kommer att behandlas som externa delar. Det genererar HTML som är lämplig för ett brett urval av webbläsare. |
| [NoEmbedding](#NoEmbedding) | Tvingar att separera refererade filer (Css, Bilder, Teckensnitt). Detta tillvägagångssätt skapar en uppsättning filer, men den totala storleken på utdata blir mindre (eftersom ingen Base64-kodning av binärer används). Sådant tillvägagångssätt genererar också HTML som är lämplig för ett brett urval av webbläsare. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

Tvingar inbäddning av alla refererade filer (Css, Bilder, Teckensnitt) i den genererade HTML-markupen (dvs. i själva HTML). Detta tillvägagångssätt skapar en HTML-fil, men den totala storleken på utdata blir större (eftersom Base64-kodning av binärer används) och inte alla webbläsare (särskilt äldre) kan framgångsrikt bearbeta binärer som är inbäddade i HTML. Men det möjliggör att få HTML som innehåller hela resultatet utan några extra filer.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

Tvingar att separera alla refererade filer förutom CSS (bilder och teckensnitt). Det vill säga, CSS kommer att bäddas in i resultat-HTML, och alla andra refererade filer (bilder och teckensnitt) kommer att behandlas som externa delar. Det genererar HTML som är lämplig för ett brett urval av webbläsare.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

Tvingar att separera refererade filer (Css, Bilder, Teckensnitt). Detta tillvägagångssätt skapar en uppsättning filer, men den totala storleken på utdata blir mindre (eftersom ingen Base64-kodning av binärer används). Sådant tillvägagångssätt genererar också HTML som är lämplig för ett brett urval av webbläsare.
