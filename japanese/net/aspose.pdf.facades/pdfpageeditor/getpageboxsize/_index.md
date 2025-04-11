---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor メソッド。ドキュメント内の指定されたボックスのサイズを返します
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize メソッド

ドキュメント内の指定されたボックスのサイズを返します。

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | ページインデックス。ドキュメントのページは1から番号が付けられます。 |
| pageBoxName | String | ボックスのタイプ名。有効な値は次のとおりです: "art", "bleed", "crop", "media", "trim". |

### 戻り値

要求されたボックスを含む矩形。

## 例

以下の例は、1ページ目のメディアボックスを取得する方法を示しています:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### 参照

* クラス [PdfPageEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)