---
title: UniqueSuffix
second_title: Aspose.PDF for .NET API Referansı
description: Formlar birleştirildiğinde benzersiz olması için alan adına eklenen son ekin biçimi. Bu dize sayılarla değiştirilecek NUM alt dize içermelidir. Örneğin UniqueSuffix  ABCNUM ise o zaman için alan alanAdı adları şöyle olacaktır alanAdıABC1 alanAdıABC2 alanAdıABC3 vb.
type: docs
weight: 230
url: /tr/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

Formlar birleştirildiğinde benzersiz olması için alan adına eklenen son ekin biçimi. Bu dize, sayılarla değiştirilecek %NUM% alt dize içermelidir. Örneğin, UniqueSuffix = "ABC%NUM%" ise, o zaman için alan "alanAdı" adları şöyle olacaktır: alanAdıABC1, alanAdıABC2, alanAdıABC3 vb.

```csharp
public string UniqueSuffix { get; set; }
```

### Örnekler

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->