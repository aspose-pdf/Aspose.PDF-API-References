---
title: AddMarginsPct
second_title: Aspose.PDF für .NET-API-Referenz
description: Ändert die Größe des Seiteninhalts und fügt bestimmte Ränder hinzu. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben.
type: docs
weight: 260
url: /de/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Ändert die Größe des Seiteninhalts und fügt bestimmte Ränder hinzu. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | String | Pfad zum Quelldokument. |
| destination | String | Pfad, in dem das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Dokumentseiten verarbeitet. |
| leftMargin | Double | Linker Rand in Prozent der anfänglichen Seitengröße. |
| rightMargin | Double | Rechter Rand in Prozent der anfänglichen Seitengröße. |
| topMargin | Double | Oberer Rand in Prozent der anfänglichen Seitengröße. |
| bottomMargin | Double | Unterer Rand in Prozent der anfänglichen Seitengröße. |

### Rückgabewert

true, wenn die Größenänderung erfolgreich war

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    // Seiten 1, 2, 3 verarbeiten
    new int[] { 1, 2, 3}, 
    //Der linke Rand beträgt 15 % der Seitenbreite 
    15, 
    //rechter Rand beträgt 10 % der Seitenbreite
    10, 
    //Der obere Rand beträgt 20 % der Seitenbreite
    20, 
    //Unterer Rand beträgt 5 % der Seitenbreite
    5);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Ändert die Größe des Seiteninhalts und fügt bestimmte Ränder hinzu. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | Stream | Stream, der das Quelldokument enthält. |
| destination | Stream | Stream, wo das resultierende Dokument gespeichert wird. |
| pages | Int32[] | Array von Seitenindizes. Wenn null, werden alle Dokumentseiten verarbeitet. |
| leftMargin | Double | Linker Rand in Prozent der anfänglichen Seitengröße. |
| rightMargin | Double | Rechter Rand in Prozent der anfänglichen Seitengröße. |
| topMargin | Double | Oberer Rand in Prozent der anfänglichen Seitengröße. |
| bottomMargin | Double | Unterer Rand in Prozent der anfänglichen Seitengröße. |

### Rückgabewert

wahr, wenn die Aktion erfolgreich ausgeführt wurde.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    // Seiten 1, 2, 3 verarbeiten
    new int[] { 1, 2, 3}, 
    //Der linke Rand beträgt 15 % der Seitenbreite 
    15, 
    //rechter Rand beträgt 10 % der Seitenbreite
    10, 
    //Der obere Rand beträgt 20 % der Seitenbreite
    20, 
    //Unterer Rand beträgt 5 % der Seitenbreite
    5);
    dest.Close();
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->