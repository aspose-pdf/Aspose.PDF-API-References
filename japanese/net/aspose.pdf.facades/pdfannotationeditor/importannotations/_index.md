---
title: PdfAnnotationEditor.ImportAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor メソッド。別の PDF ドキュメントの配列からドキュメントに指定された注釈をインポートします
type: docs
weight: 90
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## ImportAnnotations(string[], AnnotationType[]) {#importannotations_3}

別の PDF ドキュメントの配列からドキュメントに指定された注釈をインポートします。

```csharp
public void ImportAnnotations(string[] annotFile, AnnotationType[] annotType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| annotFile | String[] | ソース注釈を含む PDF ドキュメントのパスの配列。 |
| annotType | AnnotationType[] | インポートする注釈の種類の配列。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotations(paths, annotTypes);
editor.Save("example_out.pdf");
```

### 参照

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(string[]) {#importannotations_2}

別の PDF ドキュメントの配列からドキュメントに注釈をインポートします。

```csharp
public void ImportAnnotations(string[] annotFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| annotFile | String[] | ソース注釈を含む PDF ドキュメントのパスの配列。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] paths = new string[2] {"with_annots1.pdf", "with_annots2.pdf"};
editor.ImportAnnotations(paths);
editor.Save("example_out.pdf");
```

### 参照

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[], AnnotationType[]) {#importannotations_1}

別の PDF ドキュメントストリームの配列からドキュメントに指定された注釈をインポートします。

```csharp
public void ImportAnnotations(Stream[] annotFileStream, AnnotationType[] annotType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| annotFileStream | Stream[] | ソース注釈を含む PDF ドキュメントのストリームの配列。 |
| annotType | AnnotationType[] | インポートする注釈の種類。 |

## 例

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

### 参照

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotations(Stream[]) {#importannotations}

別の PDF ドキュメントストリームの配列からドキュメントに注釈をインポートします。

```csharp
public void ImportAnnotations(Stream[] annotFileStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| annotFileStream | Stream[] | ソース注釈を含む PDF ドキュメントのストリームの配列。 |

## 例

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

### 参照

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)