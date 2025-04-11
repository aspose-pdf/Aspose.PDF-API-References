---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor メソッド。指定されたページ範囲の指定されたタイプの注釈を修正します。次の注釈プロパティを修正することをサポートします: 修正済み、タイトル、内容、色、件名、およびオープン
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations メソッド

指定されたページ範囲の指定されたタイプの注釈を修正します。次の注釈プロパティを修正することをサポートします: 修正済み、タイトル、内容、色、件名、およびオープン。

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| start | Int32 | 開始ページ番号。 |
| end | Int32 | 終了ページ番号。 |
| annotation | Annotation | 新しいプロパティを含む注釈オブジェクト。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [Annotation](../../../aspose.pdf.annotations/annotation/)
* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)