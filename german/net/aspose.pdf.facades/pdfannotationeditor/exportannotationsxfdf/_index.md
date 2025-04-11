---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-Methode. Exportiert den Inhalt der angegebenen Annotationsarten in XFDF
type: docs
weight: 50
url: /de/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Exportiert den Inhalt der angegebenen Annotationsarten in XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlOutputStream | Stream | Der Ausgabestream für XFDF. |
| start | Int32 | Startseite, von der die Anmerkungen des Dokuments exportiert werden. |
| end | Int32 | Endseite, zu der die Anmerkungen des Dokuments exportiert werden. |
| annotTypes | String[] | Das Array der Annotationsarten, die exportiert werden müssen. |

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Siehe auch

* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Exportiert den Inhalt der angegebenen Annotationsarten in XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlOutputStream | Stream | Der Ausgabestream für XFDF. |
| start | Int32 | Startseite, von der die Anmerkungen des Dokuments exportiert werden. |
| end | Int32 | Endseite, zu der die Anmerkungen des Dokuments exportiert werden. |
| annotTypes | AnnotationType[] | Das Array der Annotationsarten, die exportiert werden müssen. |

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Siehe auch

* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)