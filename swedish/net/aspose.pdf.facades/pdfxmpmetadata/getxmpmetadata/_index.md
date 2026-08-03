---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfXmpMetadata-metoden. Hämta XmpMetadata för den angivna pdf i XML-format"
type: docs
weight: 190
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Hämta XmpMetadata för den angivna pdf-filen i XML-format.

```csharp
public byte[] GetXmpMetadata()
```

### Returvärde

Byte för XmpMetadata.

## Exempel

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### Se även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Hämta en del av XmpMetadata för den angivna pdf-filen enligt ett metanamn.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | String | Metadatnamn. |

### Returvärde

Byte av metadata.

## Exempel

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### Se även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


