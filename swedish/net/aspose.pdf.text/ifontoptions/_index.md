---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.IFontOptions-gränssnitt. Användbara egenskaper för att justera teckensnittsbeteende
type: docs
weight: 10610
url: /sv/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions-gränssnitt

Användbara egenskaper för att justera teckensnittsbeteende

```csharp
public interface IFontOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Ibland är det inte möjligt att bädda in önskat teckensnitt i dokumentet. Det finns många anledningar, till exempel licensbegränsningar eller när önskat teckensnitt inte hittades på destinationens dator. När denna situation uppstår är det inte enkelt att upptäcka, eftersom önskat teckensnitt är inbäddat via en uppsättning egenskapsflaggor Font.IsEmbedded = true; Självklart är det möjligt att läsa denna egenskap omedelbart efter att den har ställts in, men det är inte en bekväm metod. Flaggan NotifyAboutFontEmbeddingError tvingar fram ett undantagsmekanism för fall när försök att bädda in teckensnitt misslyckas. Om denna flagga är inställd kommer ett undantag av typen [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) att kastas. Som standard false. |

### Se Även

* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)