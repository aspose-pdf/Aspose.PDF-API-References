---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor property. Format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain NUM substring which will be replaced with numbers. For example if UniqueSuffix  ABCNUM then for field fieldName names will be fieldNameABC1 fieldNameABC2 fieldNameABC3 etc
type: docs
weight: 200
url: /net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

Format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

```csharp
public string UniqueSuffix { get; set; }
```

## Examples

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


