---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Stamp-Methode. Setzt die PDF-Datei und die Seitenzahl, die als Stempel verwendet werden soll
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Setzt die PDF-Datei und die Seitenzahl, die als Stempel verwendet werden soll.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfFile | String | Pfad zur PDF-Datei. |
| pageNumber | Int32 | Seitenzahl in der PDF-Datei |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Siehe auch

* Klasse [Stamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Setzt die PDF-Datei und die Seitenzahl, die als Stempel verwendet werden soll.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfStream | Stream | Stream, der das PDF-Dokument enthält. |
| pageNumber | Int32 | Seitenindex des Dokuments, der als Stempel verwendet wird. |

## Beispiele

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Siehe auch

* Klasse [Stamp](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)