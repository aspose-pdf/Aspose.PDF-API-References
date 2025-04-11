---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Ändert die Größe des Inhalts der Seiten des Dokuments
type: docs
weight: 450
url: /de/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Ändert die Größe des Inhalts der Seiten im Dokument. Wenn die Seite verkleinert wird, werden leere Ränder um die Seite hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zur Quelldatei. |
| pages | Int32[] | Array von Seiten, die geändert werden sollen. |
| parameters | ContentsResizeParameters | Größenänderungsparameter. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, mit dem Unterschied, dass die TryResizeContents-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Ändert die Größe des Inhalts der Seiten im Dokument. Wenn die Seite verkleinert wird, werden leere Ränder um die Seite hinzugefügt. Das Ergebnis wird im HttpResponse-Objekt gespeichert.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream der Quelldatei. |
| pages | Int32[] | Array von Seiten, die geändert werden sollen. |
| parameters | ContentsResizeParameters | Größenänderungsparameter. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, mit dem Unterschied, dass die TryResizeContents-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Ändert die Größe des Inhalts der Seiten des Dokuments.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream mit dem Quelldokument. |
| destination | Stream | Stream mit dem Zieldokument. |
| pages | Int32[] | Array von Seitenindizes. |
| parameters | ContentsResizeParameters | Größenänderungsparameter. |

### Rückgabewert

Gibt true zurück, wenn der Erfolg.

## Anmerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, mit dem Unterschied, dass die TryResizeContents-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Siehe auch

* Klasse [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Ändert die Größe des Inhalts der Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Größe des Inhalts wird in Standardraumeinheiten angegeben.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream, der das Quelldokument enthält. |
| destination | Stream | Stream, in dem das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Dokumentseiten verarbeitet. |
| newWidth | Double | Neue Breite des Seiteninhalts in Standardraumeinheiten. |
| newHeight | Double | Neue Höhe des Seiteninhalts in Standardraumeinheiten. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, mit dem Unterschied, dass die TryResizeContents-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
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

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Ändert die Größe des Inhalts der Seiten im Dokument. Wenn die Seite verkleinert wird, werden leere Ränder um die Seite hinzugefügt.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
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

## Anmerkungen

Die TryResizeContents-Methode ist wie die ResizeContents-Methode, mit dem Unterschied, dass die TryResizeContents-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Siehe auch

* Klasse [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)