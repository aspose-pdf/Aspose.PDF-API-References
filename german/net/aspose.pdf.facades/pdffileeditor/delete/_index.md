---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue Pdf-Datei
type: docs
weight: 270
url: /de/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue Pdf-Datei.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Eingabedatei. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputFile | String | Pfad zur Ausgabedatei. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Löscht Seiten, die durch ein Zahlenarray aus der Eingabedatei angegeben sind, und speichert sie als neue Pdf-Datei.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedatei-Stream. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputStream | Stream | Ausgabedatei-Stream. |

### Rückgabewert

Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)