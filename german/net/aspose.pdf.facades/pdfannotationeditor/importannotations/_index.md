---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-Methode. Importiert die angegebenen Anmerkungen in das Dokument aus einem Array von anderen PDF-Dokumenten
type: docs
weight: 90
url: /de/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

Importiert die angegebenen Anmerkungen in das Dokument aus einem Array von anderen PDF-Dokumenten.

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| annotFile | String[] | Das Array von Pfaden zu PDF-Dokumenten, die Quellanmerkungen enthalten. |
| annotType | AnnotationType[] | Das Array von Anmerkungstypen, die importiert werden sollen. |

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### Siehe auch

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

Importiert Anmerkungen in das Dokument aus einem Array von anderen PDF-Dokumenten.

```csharp
public void ImportAnnotations(string[] annotFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| annotFile | String[] | Das Array von Pfaden zu PDF-Dokumenten, die Quellanmerkungen enthalten. |

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

Importiert die angegebenen Anmerkungen in das Dokument aus einem Array von anderen PDF-Dokumenten-Streams.

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| annotFileStream | Stream[] | Das Array von Streams von PDF-Dokumenten, die Quellanmerkungen enthalten. |
| annotType | AnnotationType[] | Die Anmerkungstypen, die importiert werden sollen. |

## Beispiele

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

### Siehe auch

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

Importiert Anmerkungen in das Dokument aus einem Array von anderen PDF-Dokumenten-Streams.

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| annotFileStream | Stream[] | Das Array von Streams von PDF-Dokumenten, die Quellanmerkungen enthalten. |

## Beispiele

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

### Siehe auch

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)