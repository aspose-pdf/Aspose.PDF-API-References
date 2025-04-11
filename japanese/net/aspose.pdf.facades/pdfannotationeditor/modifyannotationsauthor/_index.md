---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor メソッド。指定されたページ範囲の注釈の著者を変更します。
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor メソッド

指定されたページ範囲の注釈の著者を変更します。

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| start | Int32 | 開始ページ番号。 |
| end | Int32 | 終了ページ番号。 |
| srcAuthor | String | 変更する著者。 |
| desAuthor | String | 新しい著者。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)