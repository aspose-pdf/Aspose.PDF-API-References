---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Eigenschaft. Format des Suffix, das zum Feldnamen hinzugefügt wird, um ihn einzigartig zu machen, wenn Formulare zusammengefügt werden. Dieser String muss den SUBSTRING NUM enthalten, der durch Zahlen ersetzt wird. Zum Beispiel, wenn UniqueSuffix ABCNUM ist, dann werden für das Feld fieldName die Namen fieldNameABC1, fieldNameABC2, fieldNameABC3 usw. sein.
type: docs
weight: 200
url: /de/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.EinzigartigerSuffix-Eigenschaft

Format des Suffix, das zum Feldnamen hinzugefügt wird, um ihn einzigartig zu machen, wenn Formulare zusammengefügt werden. Dieser String muss den %NUM% SUBSTRING enthalten, der durch Zahlen ersetzt wird. Zum Beispiel, wenn UniqueSuffix = "ABC%NUM%" ist, dann werden für das Feld "fieldName" die Namen sein: fieldNameABC1, fieldNameABC2, fieldNameABC3 usw.

```csharp
public string UniqueSuffix { get; set; }
```

## Beispiele

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)