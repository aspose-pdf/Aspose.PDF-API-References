---
title: "Aspose::Pdf::HtmlSaveOptions::HtmlMarkupGenerationModes enum"
linktitle: "HtmlMarkupGenerationModes"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::HtmlMarkupGenerationModes enum. Ibland finns specifika krav på den skapade HTML:n. Denna enum definierar HTML-förberedelselägen som kan användas under konvertering av PDF till HTML för att matcha sådana specifika krav i C++."
type: docs
weight: 5500
url: /sv/cpp/aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmodes/
---
## HtmlMarkupGenerationModes enum


Ibland finns specifika krav på den skapade HTML:n. Denna enum definierar HTML-förberedelselägen som kan användas under konvertering av PDF till HTML för att matcha sådana specifika krav.

```cpp
enum class HtmlMarkupGenerationModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| WriteAllHtml | 0 | Standardläge när inga specifika krav finns. Det genererade resultatet kommer att innehålla alla delar av HTML utan någon särskild ytterligare bearbetning. |
| WriteOnlyBodyContent | 1 | allt HTML-innehåll som ligger utanför HTML:s body kommer att tas bort, dvs. endast innehåll som ligger inom **<body>****</body>**-taggarna kommer att lämnas kvar |

## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
