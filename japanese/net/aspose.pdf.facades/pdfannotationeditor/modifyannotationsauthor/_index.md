---
title: "PdfAnnotationEditor.ModifyAnnotationsAuthor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfAnnotationEditor メソッド。指定されたページ範囲の注釈の作成者を変更します"
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor method

指定されたページ範囲の注釈の作成者を変更します。

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| start | Int32 | 開始ページ番号です。 |
| end | Int32 | 終了ページ番号です。 |
| srcAuthor | String | 変更対象の作成者です。 |
| desAuthor | String | 新しい作成者です。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


