---
title: "Enum HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes enum. Denna enum listar möjliga lägen för inbäddning av filer som refereras i HTML. Den gör det möjligt att styra om refererade filer HTML, Fonts, Images, CSSes ska bäddas in i huvud-HTML-filen eller genereras som separata binära enheter."
type: docs
weight: 5840
url: /sv/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

Denna enum listar möjliga lägen för inbäddning av filer som refereras i HTML. Den gör det möjligt att styra om refererade filer (HTML, Fonts, Images, CSSes) ska bäddas in i huvud-HTML-filen eller genereras som separata binära enheter.

```csharp
public enum PartsEmbeddingModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Tvingar inbäddning av alla refererade filer (Css, Images, Fonts) i den genererade HTML-markupen (dvs. i HTML själv). Detta tillvägagångssätt genererar en HTML-fil, men den totala storleken på utdata blir större (på grund av Base64-kodning av binärer) och inte alla webbläsare (särskilt äldre) kan framgångsrikt bearbeta binärer som är inbäddade i HTML. Men det möjliggör att få en HTML som innehåller hela resultatet utan några ytterligare filer. |
| EmbedCssOnly | `1` | Tvingar att separera alla refererade filer förutom CSS (Images och Fonts). Det vill säga, CSS kommer att bäddas in i den resulterande HTML:n, och alla andra refererade filer (Images och Fonts) kommer att behandlas som externa delar. Detta genererar HTML som är lämplig för ett brett urval av webbläsare. |
| NoEmbedding | `2` | Tvingar att separera refererade filer (Css, Images, Fonts). Detta tillvägagångssätt genererar en uppsättning filer, men den totala storleken på utdata blir mindre (eftersom ingen Base64-kodning av binärer används). Sådant tillvägagångssätt genererar också HTML som är lämplig för ett brett urval av webbläsare. |

### Se även

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


