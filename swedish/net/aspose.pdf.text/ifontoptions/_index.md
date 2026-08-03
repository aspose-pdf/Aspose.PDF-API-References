---
title: "Gränssnitt IFontOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.IFontOptions‑gränssnitt. Användbara egenskaper för att finjustera teckensnittsbeteende"
type: docs
weight: 10790
url: /sv/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

Användbara egenskaper för att finjustera Font-beteende.

```csharp
public interface IFontOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Det är ibland inte möjligt att bädda in önskat teckensnitt i dokumentet. Det finns många orsaker, till exempel licensrestriktioner eller när det önskade teckensnittet inte hittades på mål‑datorn. När denna situation uppstår är den inte enkel att upptäcka, eftersom det önskade teckensnittet är inbäddat via egendomsflaggan Font.IsEmbedded = true; Naturligtvis går det att läsa denna egenskap omedelbart efter att den satts, men det är inte ett bekvämt tillvägagångssätt. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall då försök att bädda in teckensnittet misslyckas. Om denna flagga är satt kastas ett undantag av typen [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/). Standardvärdet är false. |

### Se även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


