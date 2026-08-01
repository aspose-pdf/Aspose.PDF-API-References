---
title: "PdfPageEditor.GetPageBoxSize"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfPageEditor メソッド。ドキュメント内の指定されたボックスのサイズを返します"
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize method

Document 内の指定されたボックスのサイズを返します。

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | Int32 | ページインデックス。ドキュメントのページは 1 から番号付けされます。 |
| pageBoxName | String | ボックスタイプ名。有効な値は: "art", "bleed", "crop", "media", "trim"。 |

### 戻り値

要求されたボックスを含む矩形。

## 例

次の例は、1 ページ目の media ボックスを取得する方法を示しています。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### 関連項目

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


