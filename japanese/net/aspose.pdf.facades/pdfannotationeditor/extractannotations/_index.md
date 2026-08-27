---
title: "PdfAnnotationEditor.ExtractAnnotations"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfAnnotationEditor メソッド。指定されたタイプの注釈のリストを取得します。"
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

指定されたタイプの注釈一覧を取得します。

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| start | Int32 | 注釈が選択される開始ページ。 |
| end | Int32 | 注釈が選択される終了ページ。 |
| annotTypes | String[] | 必要な注釈タイプの配列。 |

### 戻り値

注釈リスト。

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### 関連項目

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

指定されたタイプの注釈一覧を取得します。

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| start | Int32 | 注釈が選択される開始ページ。 |
| end | Int32 | 注釈が選択される終了ページ。 |
| annotTypes | AnnotationType[] | 必要な注釈タイプの配列。 |

### 戻り値

注釈リスト。

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### 関連項目

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


