---
title: GetPageSize
second_title: Aspose.PDF für .NET-API-Referenz
description: Gibt die Seitengröße der angegebenen Seite zurück.
type: docs
weight: 160
url: /de/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

Gibt die Seitengröße der angegebenen Seite zurück.

```csharp
public PageSize GetPageSize(int page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Seitenindex. Dokumentseiten sind von 1 nummeriert. |

### Rückgabewert

Das Ergebnis ist eine Instanz von PageSize. Verwenden Sie die Eigenschaften Breite und Höhe des zurückgegebenen Objekts, um Seitenbreite und -höhe zu erhalten.

### Beispiele

Das folgende Beispiel zeigt die Verwendung der GetPageSize-Methode:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfPageEditor](../../pdfpageeditor)
* namensraum [Aspose.Pdf.Facades](../../pdfpageeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
