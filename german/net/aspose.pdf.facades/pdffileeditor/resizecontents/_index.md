---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Ändert die Größe des Inhalts der Seiten des Dokuments
type: docs
weight: 320
url: /de/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

Ändert die Größe des Inhalts der Seiten des Dokuments.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream mit dem Quelldokument. |
| destination | Stream | Stream mit dem Zieldokument. |
| pages | Int32[] | Array von Seitenindizes. |
| parameters | ContentsResizeParameters | Größenänderungsparameter. |

### Rückgabewert

Gibt true zurück, wenn der Vorgang erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Siehe auch

* Klasse [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Ändert die Größe des Inhalts der Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Größe des Inhalts wird in Standardraumeinheiten angegeben.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream, der das Quelldokument enthält. |
| destination | Stream | Stream, in dem das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Seiten des Dokuments verarbeitet. |
| newWidth | Double | Neue Breite des Seiteninhalts in Standardraumeinheiten. |
| newHeight | Double | Neue Höhe des Seiteninhalts in Standardraumeinheiten. |

### Rückgabewert

True, wenn die Größenänderung erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

Ändert die Größe des Inhalts der Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Größe des Inhalts wird in Standardraumeinheiten angegeben.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zum Quelldokument. |
| destination | String | Pfad, wo das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Seiten des Dokuments verarbeitet. |
| newWidth | Double | Neue Breite des Seiteninhalts in Standardraumeinheiten. |
| newHeight | Double | Neue Höhe des Seiteninhalts in Standardraumeinheiten. |

### Rückgabewert

true, wenn die Größenänderung erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

Ändert die Größe des Inhalts der Seiten im Dokument. Wenn die Seite verkleinert wird, werden leere Ränder um die Seite hinzugefügt.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zum Quelldokument. |
| destination | String | Pfad zum Zieldokument. |
| pages | Int32[] | Array von Seitenindizes (Seitenindex beginnt bei 1). |
| parameters | ContentsResizeParameters | Parameter zur Größenänderung der Seite. |

### Rückgabewert

true, wenn die Größenänderung erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Siehe auch

* Klasse [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

Ändert die Größe der Seiten des Dokuments. Leere Ränder werden um die verkleinerte Seite hinzugefügt.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Document | Quelldokument. |
| pages | Int32[] | Liste der Seitenindizes. |
| parameters | ContentsResizeParameters | Größenänderungsparameter. |

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

Ändert die Größe der Seiten des Dokuments. Leere Ränder werden um die verkleinerte Seite hinzugefügt.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Document | Quelldokument. |
| parameters | ContentsResizeParameters | Größenänderungsparameter. |

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)