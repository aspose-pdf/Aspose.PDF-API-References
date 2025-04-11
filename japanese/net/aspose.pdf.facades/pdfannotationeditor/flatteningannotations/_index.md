---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor メソッド。ドキュメント内のすべての注釈をフラット化します
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## FlatteningAnnotations() {#flatteningannotations}

ドキュメント内のすべての注釈をフラット化します。

```csharp
public void FlatteningAnnotations()
```

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### 関連項目

* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## FlatteningAnnotations(FlattenSettings) {#flatteningannotations_1}

ドキュメント内のすべての注釈をフラット化します。

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| flattenSettings | FlattenSettings | フラット化のモードを指定します。 |

### 関連項目

* クラス [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## FlatteningAnnotations(int, int, AnnotationType[]) {#flatteningannotations_2}

指定されたタイプの注釈をフラット化します。

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| start | Int32 | 開始ページ。 |
| end | Int32 | 終了ページ。 |
| annotType | AnnotationType[] | フラット化すべき注釈のタイプ。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### 関連項目

* 列挙 [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)