---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor メソッド。指定されたページのページサイズを返します
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize メソッド

指定されたページのページサイズを返します。

```csharp
public PageSize GetPageSize(int page)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | ページインデックス。ドキュメントのページは1から番号が付けられます。 |

### 戻り値

結果は PageSize のインスタンスです。返されたオブジェクトの Width および Height プロパティを使用して、ページの幅と高さを取得します。

## 例

以下の例は、GetPageSize メソッドの使用を示しています。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### 参照

* クラス [PageSize](../../../aspose.pdf/pagesize/)
* クラス [PdfPageEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)