---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Ändert die Größe des Seiteninhalts und fügt die angegebenen Ränder hinzu. Ränder werden in Standardraum-Einheiten angegeben
type: docs
weight: 220
url: /de/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Ändert die Größe des Seiteninhalts und fügt die angegebenen Ränder hinzu. Ränder werden in Standardraum-Einheiten angegeben.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream, der das Quelldokument enthält. |
| destination | Stream | Stream, in dem das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Seiten des Dokuments verarbeitet. |
| leftMargin | Double | Linker Rand. |
| rightMargin | Double | Rechter Rand. |
| topMargin | Double | Oberer Rand. |
| bottomMargin | Double | Unterer Rand. |

### Rückgabewert

true, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Ändert die Größe des Seiteninhalts und fügt die angegebenen Ränder hinzu. Ränder werden in Standardraum-Einheiten angegeben.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zum Quelldokument. |
| destination | String | Pfad, in dem das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Seiten des Dokuments verarbeitet. |
| leftMargin | Double | Linker Rand. |
| rightMargin | Double | Rechter Rand. |
| topMargin | Double | Oberer Rand. |
| bottomMargin | Double | Unterer Rand. |

### Rückgabewert

true, wenn die Größenänderung erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)