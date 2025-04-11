---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-Methode. Gibt die Größe des angegebenen Feldes im Dokument zurück
type: docs
weight: 130
url: /de/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize-Methode

Gibt die Größe des angegebenen Feldes im Dokument zurück.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Seitenindex. Dokumentseiten sind von 1 nummeriert. |
| pageBoxName | String | Name des Feldtyps. Gültige Werte sind: "art", "bleed", "crop", "media", "trim". |

### Rückgabewert

Rechteck, das das angeforderte Feld enthält.

## Beispiele

Das folgende Beispiel zeigt, wie man das Medienfeld der 1. Seite erhält:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Siehe auch

* Klasse [PdfPageEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)