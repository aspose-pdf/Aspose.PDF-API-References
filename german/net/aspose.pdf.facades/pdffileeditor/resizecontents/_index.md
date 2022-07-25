---
title: ResizeContents
second_title: Aspose.PDF für .NET-API-Referenz
description: Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird werden um die Seite herum leere Ränder hinzugefügt.
type: docs
weight: 350
url: /de/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_4}

Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
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
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Siehe auch

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_7}

Passt Seiten des Dokuments an. Leere Ränder werden um die verkleinerte Seite herum hinzugefügt.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Document | Quelldokument. |
| pages | Int32[] | Liste der Seitenindizes. |
| parameters | ContentsResizeParameters | Parameter ändern. |

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Siehe auch

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_6}

Passt Seiten des Dokuments an. Leere Ränder werden um die verkleinerte Seite herum hinzugefügt.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Document | Quelldokument. |
| parameters | ContentsResizeParameters | Parameter ändern. |

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Siehe auch

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents_1}

Ändert die Seiteninhalte des Dokuments.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
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
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Siehe auch

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_2}

Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Neue Größe des Inhalts wird in Standard-Leerzeicheneinheiten angegeben.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

True, wenn die Größenänderung erfolgreich war.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
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

## ResizeContents(string, string, int[], double, double) {#resizecontents_5}

Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Neue Größe des Inhalts wird in Standard-Leerzeicheneinheiten angegeben.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zum Quelldokument. |
| destination | String | Pfad, in dem das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Dokumentseiten verarbeitet. |
| newWidth | Double | Neue Breite des Seiteninhalts in Standardabstandseinheiten. |
| newHeight | Double | Neue Höhe des Seiteninhalts in Standardabstandseinheiten. |

### Rückgabewert

true, wenn die Größenänderung erfolgreich war.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
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

## ResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#resizecontents_3}

Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert.

```csharp
public bool ResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zur Quelldatei. |
| pages | Int32[] | Array von Seiten, deren Größe geändert werden soll. |
| parameters | ContentsResizeParameters | Parameter ändern. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## ResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#resizecontents}

Ändert die Seiteninhalte im Dokument. Wenn die Seite verkleinert wird, werden um die Seite herum leere Ränder hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert.

```csharp
public bool ResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream der Quelldatei. |
| pages | Int32[] | Array von Seiten, deren Größe geändert werden soll. |
| parameters | ContentsResizeParameters | Parameter ändern. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
