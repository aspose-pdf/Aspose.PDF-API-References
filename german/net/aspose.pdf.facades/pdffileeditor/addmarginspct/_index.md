---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Ändert die Seiteninhalte und fügt die angegebenen Ränder hinzu. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben
type: docs
weight: 230
url: /de/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Ändert die Seiteninhalte und fügt die angegebenen Ränder hinzu. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream, der das Quelldokument enthält. |
| destination | Stream | Stream, in dem das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Seiten des Dokuments verarbeitet. |
| leftMargin | Double | Linker Rand in Prozent der ursprünglichen Seitengröße. |
| rightMargin | Double | Rechter Rand in Prozent der ursprünglichen Seitengröße. |
| topMargin | Double | Oberer Rand in Prozent der ursprünglichen Seitengröße. |
| bottomMargin | Double | Unterer Rand in Prozent der ursprünglichen Seitengröße. |

### Rückgabewert

true, wenn die Aktion erfolgreich ausgeführt wurde.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Ändert die Seiteninhalte und fügt die angegebenen Ränder hinzu. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zum Quelldokument. |
| destination | String | Pfad, wo das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Seiten des Dokuments verarbeitet. |
| leftMargin | Double | Linker Rand in Prozent der ursprünglichen Seitengröße. |
| rightMargin | Double | Rechter Rand in Prozent der ursprünglichen Seitengröße. |
| topMargin | Double | Oberer Rand in Prozent der ursprünglichen Seitengröße. |
| bottomMargin | Double | Unterer Rand in Prozent der ursprünglichen Seitengröße. |

### Rückgabewert

true, wenn die Größenänderung erfolgreich war

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)