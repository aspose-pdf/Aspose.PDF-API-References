---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Teilt die PDF-Datei in Einzelblattdokumente auf
type: docs
weight: 370
url: /de/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

Teilt die PDF-Datei in Einzelblattdokumente auf.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-PDF-Dateiname. |

### Rückgabewert

Ausgabe-PDF-Streams, jeder Stream puffert ein Einzelblatt-PDF-Dokument.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Teilt die Pdf-Datei in Einzelblattdokumente auf.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-Pdf-Stream. |

### Rückgabewert

Array von Speicher-Streams, die Seiten des Dokuments enthalten.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Teilt die Pdf-Datei in Einzelblattdokumente auf und speichert sie im angegebenen Pfad. Der Pfad wird durch den Feldnamen-Template angegeben.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabedateiname. |
| fileNameTemplate | String | Vorlage des resultierenden Dateinamens. Muss %NUM% enthalten, das durch die Seitennummer ersetzt wird. Wenn z.B. c:/dir/page%NUM%.pdf angegeben ist, haben die resultierenden Dateien die folgenden Namen: c:/dir/page1.pdf, c:/dir/page2.pdf usw. |

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Teilt die Pdf-Datei in Einzelblattdokumente auf und speichert sie im angegebenen Pfad. Der Pfad wird durch den Feldnamen-Template angegeben.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Quell-Dokuments. |
| fileNameTemplate | String | Vorlage des resultierenden Dateinamens. Muss %NUM% enthalten, das durch die Seitennummer ersetzt wird. Wenn z.B. c:/dir/page%NUM%.pdf angegeben ist, haben die resultierenden Dateien die folgenden Namen: c:/dir/page1.pdf, c:/dir/page2.pdf usw. |

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)