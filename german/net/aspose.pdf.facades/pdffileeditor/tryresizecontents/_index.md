---
title: TryResizeContents
second_title: Aspose.PDF für .NET-API-Referenz
description: Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird werden um die Seite herum leere Ränder hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert.
type: docs
weight: 480
url: /de/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents_3}

Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zur Quelldatei. |
| pages | Int32[] | Array von Seiten, deren Größe geändert werden soll. |
| parameters | ContentsResizeParameters | Parameter ändern. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, außer dass die TryResizeContents -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream der Quelldatei. |
| pages | Int32[] | Array von Seiten, deren Größe geändert werden soll. |
| parameters | ContentsResizeParameters | Parameter ändern. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, außer dass die TryResizeContents -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Ändert die Seiteninhalte des Dokuments.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Mit Quelldokument streamen. |
| destination | Stream | Streamen Sie mit dem Zieldokument. |
| pages | Int32[] | Array von Seitenindizes. |
| parameters | ContentsResizeParameters | Parameter ändern. |

### Rückgabewert

Gibt bei Erfolg true zurück.

### Bemerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, außer dass die TryResizeContents -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //linker Rand = 10 % der Seitenbreite
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //neue Inhaltsbreite automatisch berechnet als Breite - linker Rand - rechter Rand (100% - 10% - 10% = 80%)
    null,
    //rechter Rand beträgt 10 % der Seite 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //oberer Rand = 10% der Höhe
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //neue Inhaltshöhe wird automatisch berechnet (ähnlich Breite)
    null,
    //untere Marge ist 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Siehe auch

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_2}

Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Neue Größe des Inhalts wird in Standard-Leerzeicheneinheiten angegeben.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream, der das Quelldokument enthält. |
| destination | Stream | Stream, wo das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Dokumentseiten verarbeitet. |
| newWidth | Double | Neue Breite des Seiteninhalts in Standardabstandseinheiten. |
| newHeight | Double | Neue Höhe des Seiteninhalts in Standardabstandseinheiten. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, außer dass die TryResizeContents -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
// Größe aller Seiten des Dokuments ändern
null, 
//neue Inhaltsbreite = 200
200, 
//neue Inhaltshöhe = 300
300);
// Restbereich der Seite ist leer
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_4}

Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad des Quelldokuments. |
| destination | String | Zieldokumentpfad. |
| pages | Int32[] | Array von Seitenindizes (Seitenindex beginnt bei 1). |
| parameters | ContentsResizeParameters | Parameter der Seitengrößenänderung. |

### Rückgabewert

true, wenn die Größenänderung erfolgreich war.

### Bemerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, außer dass die TryResizeContents -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //linker Rand = 10 % der Seitenbreite
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //neue Inhaltsbreite automatisch berechnet als Breite - linker Rand - rechter Rand (100% - 10% - 10% = 80%)
    null,
    //rechter Rand beträgt 10 % der Seite 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //oberer Rand = 10% der Höhe
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //neue Inhaltshöhe wird automatisch berechnet (ähnlich Breite)
    null,
    //untere Marge ist 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Siehe auch

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
