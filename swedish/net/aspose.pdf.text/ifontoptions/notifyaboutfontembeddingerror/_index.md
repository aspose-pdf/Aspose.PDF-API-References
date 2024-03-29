---
title: NotifyAboutFontEmbeddingError
second_title: Aspose.PDF för .NET API Referens
description: Ibland är det inte möjligt att bädda in önskat typsnitt i dokumentet. Det finns många anledningar till exempel licensbegränsningar eller när önskat teckensnitt inte hittades på destinationsdatorn. När denna situation uppstår är det inte bara att upptäcka eftersom önskat teckensnitt är inbäddat via uppsättningen av egenskapsflaggan Font.IsEmbedded  true Naturligtvis är det möjligt att läsa den här egenskapen direkt efter att den ställts in men det är inte bekvämt tillvägagångssätt. Flagga NotifyAboutFontEmbeddingError tillämpar undantagsmekanismen för fall då försöket att bädda in teckensnitt misslyckades. Om denna flagga är inställd är ett undantag för type FontEmbeddingExceptionaspose.pdf/fontembeddingexception kommer att kastas. Som standard false.
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

Ibland är det inte möjligt att bädda in önskat typsnitt i dokumentet. Det finns många anledningar, till exempel licensbegränsningar eller när önskat teckensnitt inte hittades på destinationsdatorn. När denna situation uppstår är det inte bara att upptäcka, eftersom önskat teckensnitt är inbäddat via uppsättningen av egenskapsflaggan Font.IsEmbedded = true; Naturligtvis är det möjligt att läsa den här egenskapen direkt efter att den ställts in men det är inte bekvämt tillvägagångssätt. Flagga NotifyAboutFontEmbeddingError tillämpar undantagsmekanismen för fall då försöket att bädda in teckensnitt misslyckades. Om denna flagga är inställd är ett undantag för type [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception) kommer att kastas. Som standard false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Se även

* interface [IFontOptions](../../ifontoptions)
* namnutrymme [Aspose.Pdf.Text](../../ifontoptions)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
