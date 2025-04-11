---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-Methode. Speichert das geänderte Dokument in eine Datei
type: docs
weight: 180
url: /de/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Speichert das geänderte Dokument in eine Datei.

```csharp
public override void Save(string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Pfad zur Datei, in der das Dokument gespeichert wird. |

## Beispiele

Das folgende Beispiel zeigt, wie man ein geändertes PDF-Dokument speichert.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Siehe auch

* Klasse [PdfPageEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Speichert das geänderte Dokument in einen Stream.

```csharp
public override void Save(Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Stream, in dem das geänderte PDF-Dokument gespeichert wird. |

## Beispiele

Das folgende Beispiel zeigt, wie man ein geändertes PDF-Dokument in einen Stream speichert.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Siehe auch

* Klasse [PdfPageEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)