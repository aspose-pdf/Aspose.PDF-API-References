---
title: "HtmlSaveOptions.ExplicitListOfSavedPages"
second_title: "Aspose.PDF för .NET API‑referens"
description: "HtmlSaveOptions egenskap. Med denna egenskap kan du explicit ange vilka sidor i dokumentet som ska konverteras. Sidor i denna lista måste ha 1‑baserade nummer, d.v.s. giltiga sidnummer måste tas från intervallet 1…NumberOfPagesInConvertedDocument. Ordningen på sidorna i listan påverkar inte deras ordning i de resulterande HTML‑sidorna; i resultatsidorna kommer de alltid att visas i den ordning de förekommer i käll‑PDF. Om listan är null, vilket är standard, konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (amountOfPagesInDocument) kastas ett undantag."
type: docs
weight: 70
url: /sv/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages property

Med den här egenskapen kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i den här listan måste ha 1-baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i listan påverkar inte deras ordning i de resulterande HTML-sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll-PDF:en. Om listan är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Se även

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


