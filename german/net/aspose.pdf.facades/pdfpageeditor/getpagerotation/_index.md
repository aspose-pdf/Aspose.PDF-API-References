---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-Methode. Gibt die Rotation der angegebenen Seite zurück
type: docs
weight: 140
url: /de/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation-Methode

Gibt die Rotation der angegebenen Seite zurück.

```csharp
public int GetPageRotation(int page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Seitenindex. Dokumentseiten sind von 1 an nummeriert. |

### Rückgabewert

Seitenrotation in Grad.

## Beispiele

Das folgende Beispiel zeigt, wie man die Seitenrotation erhält:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Siehe auch

* Klasse [PdfPageEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)