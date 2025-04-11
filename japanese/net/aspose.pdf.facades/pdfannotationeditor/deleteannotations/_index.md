---
title: PdfAnnotationEditor.DeleteAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor メソッド。ドキュメント内のすべての注釈を削除します
type: docs
weight: 30
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

ドキュメント内のすべての注釈を削除します。

```csharp
public void DeleteAnnotations()
```

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

指定されたタイプのすべての注釈をドキュメント内で削除します。

```csharp
public void DeleteAnnotations(string annotType)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| annotType | 文字列 | 削除される注釈のタイプ。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)