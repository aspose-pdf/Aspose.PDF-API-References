---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-Methode. Gibt die Seitengröße der angegebenen Seite zurück
type: docs
weight: 160
url: /de/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize-Methode

Gibt die Seitengröße der angegebenen Seite zurück.

```csharp
public PageSize GetPageSize(int page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Seitenindex. Dokumentseiten sind von 1 an nummeriert. |

### Rückgabewert

Das Ergebnis ist eine Instanz von PageSize. Verwenden Sie die Eigenschaften Width und Height des zurückgegebenen Objekts, um die Seitenbreite und -höhe zu erhalten.

## Beispiele

Das folgende Beispiel demonstriert die Verwendung der GetPageSize-Methode:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfPageEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)