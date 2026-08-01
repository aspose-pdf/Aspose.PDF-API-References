---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfAnnotationEditor メソッド。指定されたページ範囲の指定されたタイプの注釈を変更します。次の注釈プロパティ（Modified、Title、Contents、Color、Subject、Open）を変更することをサポートします。"
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

指定されたページ範囲の特定のタイプの注釈を変更します。次の注釈プロパティの変更をサポートしています：Modified、Title、Contents、Color、Subject、Open。

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| start | Int32 | 開始ページ番号です。 |
| end | Int32 | 終了ページ番号です。 |
| 注釈 | 注釈 | 注釈オブジェクトには新しいプロパティが含まれています。 |

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

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


