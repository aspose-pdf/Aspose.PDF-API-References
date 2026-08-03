---
title: "PdfAnnotationEditor.ImportAnnotations"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor-metod. Importerar de angivna annoteringarna till dokumentet från en array av andra PDF-dokument."
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Importerar de specificerade annotationerna till dokument från en array av andra PDF-dokument.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotFile | String[] | Arrayen med sökvägar till PDF-dokument som innehåller källannoteringar. |
| annotType | AnnotationType[] | Arrayen av annotationstyper som ska importeras. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### Se även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Importerar annotationer till dokument från en array av andra PDF-dokument.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotFile | String[] | Arrayen med sökvägar till PDF-dokument som innehåller källannoteringar. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Importerar de specificerade annotationerna till dokument från en array av andra PDF-dokumentströmmar.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotFileStream | Stream[] | Arrayen med strömmar av PDF-dokument som innehåller källannoteringar. |
| annotType | AnnotationType[] | Annoteringstyperna som ska importeras. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
stream[0]= File.OpenRead("with_annots1.pdf");
stream[1]= File.OpenRead("with_annots2.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(streams, annotTypes);
editor.Save("example_out.pdf");
stream[0].Close();
stream[1].Close();
```

### Se även

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Importerar Annotation till Document från en array av strömmar från ett annat PDF Document.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotFileStream | Stream[] | Arrayen med strömmar av PDF-dokument som innehåller källannoteringar. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
Stream[] streams = new FileStream[2];
streams[0]= File.OpenRead("with_annots1.pdf");
streams[1]= File.OpenRead("with_annots2.pdf");
editor.ImportAnnotations(streams);
editor.Save("example_out.pdf");
streams[0].Close();
streams[1].Close();
```

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


