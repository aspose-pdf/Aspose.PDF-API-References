---
title: TrySplitFromFirst
second_title: Aspose.PDF für .NET-API-Referenz
description: Teilt die PDF-Datei von der ersten Seite bis zum angegebenen Ort und speichert den vorderen Teil als neue Datei.
type: docs
weight: 490
url: /de/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_2}

Teilt die PDF-Datei von der ersten Seite bis zum angegebenen Ort und speichert den vorderen Teil als neue Datei.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quell-Pdf-Datei. |
| location | Int32 | Der Spaltpunkt. |
| outputFile | String | PDF-Datei ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Bemerkungen

Die TrySplitFromFirst-Methode ist wie die SplitFromFirst -Methode, außer dass die TrySplitFromFirst-Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Teilt vom Anfang bis zur angegebenen Position und speichert den vorderen Teil im Ausgabestream.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Quell-Pdf-Datei-Stream. |
| location | Int32 | Der Spaltpunkt. |
| outputStream | Stream | Ausgabedatei Stream. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Bemerkungen

Die Streams werden nach diesem Vorgang NICHT geschlossen. Die TrySplitFromFirst-Methode ist wie die SplitFromFirst-Methode, außer dass die TrySplitFromFirst -Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Teilt das Dokument von der ersten Seite bis zur Position und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quelldateiname. |
| location | Int32 | Split-Punkt. |
| response | HttpResponse | HttpResponse-Objekte. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TrySplitFromFirst-Methode ist wie die SplitFromFirst-Methode, außer dass die TrySplitFromFirst -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Teilt das Dokument vom Anfang bis zum angegebenen Ort auf und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Quelldokuments. |
| location | Int32 | Der Spaltpunkt. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TrySplitFromFirst-Methode ist wie die SplitFromFirst-Methode, außer dass die TrySplitFromFirst -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
