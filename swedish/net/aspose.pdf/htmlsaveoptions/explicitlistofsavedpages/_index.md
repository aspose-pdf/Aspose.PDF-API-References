---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions property. With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1based numbers. I.e. valid numbers of pages must be taken from range 1...NumberOfPagesInConvertedDocument Order of appearing of pages in this list does not affect their order in result HTML pages  in result pages allways will go in order in which they are present in source PDF. If this list is null as it is by default all pages will be converted. If any page number of this list will go out of range of present pages1amountOfPagesInDocument exception will be thrown
type: docs
weight: 70
url: /sv/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages-egenskap

Med denna egenskap kan du explicit definiera vilka sidor av dokumentet som ska konverteras. Sidor i denna lista måste ha 1-baserade nummer. D.v.s. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i denna lista påverkar inte deras ordning i resultat HTML-sidan/-sidorna; i resultatet kommer sidorna alltid att gå i den ordning de är närvarande i käll-PDF. Om denna lista är null (som den är som standard) kommer alla sidor att konverteras. Om något sidnummer i denna lista går utanför intervallet för nuvarande sidor (1-[amountOfPagesInDocument]) kommer ett undantag att kastas.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Se Även

* klass [HtmlSaveOptions](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)