---
title: GetNextImage
second_title: Aspose.PDF für .NET-API-Referenz
description: Ruft das nächste Bild aus dem PDF-Dokument ab. Hinweis ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden.
type: docs
weight: 170
url: /de/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Ruft das nächste Bild aus dem PDF-Dokument ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Datei, in der das Bild gespeichert wird |

### Rückgabewert

True ist, dass das Bild erfolgreich extrahiert wurde

### Beispiele

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### Siehe auch

* class [PdfExtractor](../../pdfextractor)
* namensraum [Aspose.Pdf.Facades](../../pdfextractor)
* Montage [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Ruft das nächste Bild aus dem PDF-Dokument mit dem angegebenen Bildformat ab. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Datei, in der das Bild gespeichert wird |
| format | ImageFormat | Das Format des Bildes. |

### Rückgabewert

True ist, dass das Bild erfolgreich extrahiert wurde

### Siehe auch

* class [PdfExtractor](../../pdfextractor)
* namensraum [Aspose.Pdf.Facades](../../pdfextractor)
* Montage [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Ruft das nächste Bild aus der PDF-Datei ab und speichert es im Stream mit dem angegebenen Bildformat.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Stream, in dem Bilddaten gespeichert werden |
| format | ImageFormat | Das Format des Bildes. |

### Rückgabewert

True, falls das Bild erfolgreich extrahiert wurde.

### Siehe auch

* class [PdfExtractor](../../pdfextractor)
* namensraum [Aspose.Pdf.Facades](../../pdfextractor)
* Montage [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Ruft das nächste Bild aus der PDF-Datei ab und speichert es im Stream.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Stream, in dem Bilddaten gespeichert werden |

### Rückgabewert

True, falls das Bild erfolgreich extrahiert wurde.

### Siehe auch

* class [PdfExtractor](../../pdfextractor)
* namensraum [Aspose.Pdf.Facades](../../pdfextractor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->