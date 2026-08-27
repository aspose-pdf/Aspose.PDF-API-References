---
title: "HtmlSaveOptions.HtmlMarkupGenerationModes"
linktitle: "HtmlSaveOptions.HtmlMarkupGenerationModes"
second_title: "Aspose.PDF för Java API-referens"
description: "Ibland finns specifika krav för att skapa HTML. Denna enum definierar HTML-förberedelselägen som kan användas under konvertering av PDF till HTML för att matcha sådana specifika krav."
type: docs
weight: 2090
url: /sv/java/com.aspose.pdf/htmlsaveoptions.htmlmarkupgenerationmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes

```
public static final class HtmlSaveOptions.HtmlMarkupGenerationModes extends com.aspose.ms.System.Enum
```

Ibland finns specifika krav på den skapade HTML:n. Denna enum definierar HTML-förberedelselägen som kan användas under konvertering av PDF till HTML för att matcha sådana specifika krav.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [WriteAllHtml](#WriteAllHtml) | Standardläge när inga specifika krav finns. Utdata kommer att genereras och innehålla alla delar av HTML utan någon särskild extra bearbetning. |
| [WriteOnlyBodyContent](#WriteOnlyBodyContent) | allt HTML-innehåll som ligger utanför HTML:s body kommer att tas bort, d.v.s. endast innehåll som finns inom {@code }-taggarna kommer att lämnas kvar. |

### WriteAllHtml {#WriteAllHtml}
```
public static final int WriteAllHtml
```

Standardläge när inga specifika krav finns. Utdata kommer att genereras och innehålla alla delar av HTML utan någon särskild extra bearbetning.

### WriteOnlyBodyContent {#WriteOnlyBodyContent}
```
public static final int WriteOnlyBodyContent
```

allt HTML-innehåll som ligger utanför HTML:s body kommer att tas bort, d.v.s. endast innehåll som finns inom {@code }-taggarna kommer att lämnas kvar.
