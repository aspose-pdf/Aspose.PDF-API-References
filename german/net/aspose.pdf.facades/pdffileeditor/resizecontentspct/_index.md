---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Inhaltsgröße wird in Prozent angegeben.
type: docs
weight: 330
url: /de/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Inhaltsgröße wird in Prozent angegeben.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream, der das Quelldokument enthält. |
| destination | Stream | Stream, in dem das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Dokumentseiten verarbeitet. |
| newWidth | Double | Neue Breite des Seiteninhalts in Prozent. |
| newHeight | Double | Neue Höhe des Seiteninhalts in Prozent. |

### Rückgabewert

true, wenn die Größenänderung erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Ändert die Größe des Inhalts von Dokumentseiten. Verkleinert den Inhalt der Seite und fügt Ränder hinzu. Die neue Inhaltsgröße wird in Prozent angegeben.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zum Quelldokument. |
| destination | String | Pfad, wo das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Dokumentseiten verarbeitet. |
| newWidth | Double | Neue Breite des Seiteninhalts in Prozent. |
| newHeight | Double | Neue Höhe des Seiteninhalts in Prozent. |

### Rückgabewert

true, wenn die Größenänderung erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)