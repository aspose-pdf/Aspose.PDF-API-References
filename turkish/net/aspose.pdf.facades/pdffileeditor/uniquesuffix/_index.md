---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor özelliği. Formlar birleştirildiğinde alan adını benzersiz hale getirmek için eklenen sarmalayıcı formatı. Bu dize, sayılarla değiştirilecek NUM alt dizesini içermelidir. Örneğin, eğer UniqueSuffix = "ABCNUM" ise, "fieldName" alanı için adlar fieldNameABC1, fieldNameABC2, fieldNameABC3 vb. olacaktır.
type: docs
weight: 200
url: /tr/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix özelliği

Formlar birleştirildiğinde alan adını benzersiz hale getirmek için eklenen sarmalayıcı formatı. Bu dize, sayılarla değiştirilecek %NUM% alt dizesini içermelidir. Örneğin, eğer UniqueSuffix = "ABC%NUM%" ise, "fieldName" alanı için adlar: fieldNameABC1, fieldNameABC2, fieldNameABC3 vb. olacaktır.

```csharp
public string UniqueSuffix { get; set; }
```

## Örnekler

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)