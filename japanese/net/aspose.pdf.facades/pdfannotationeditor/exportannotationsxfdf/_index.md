---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor メソッド。指定された注釈タイプの内容を XFDF にエクスポートします。
type: docs
weight: 50
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

指定された注釈タイプの内容を XFDF にエクスポートします。

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xmlOutputStream | Stream | 出力 XFDF ストリーム。 |
| start | Int32 | 注釈がエクスポートされる文書の開始ページ。 |
| end | Int32 | 注釈がエクスポートされる文書の終了ページ。 |
| annotTypes | String[] | エクスポートする必要がある注釈タイプの配列。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### 参照

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

指定された注釈タイプの内容を XFDF にエクスポートします。

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xmlOutputStream | Stream | 出力 XFDF ストリーム。 |
| start | Int32 | 注釈がエクスポートされる文書の開始ページ。 |
| end | Int32 | 注釈がエクスポートされる文書の終了ページ。 |
| annotTypes | AnnotationType[] | エクスポートする必要がある注釈タイプの配列。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### 参照

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)