---
title: "PdfPageEditor.GetPageSize"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfPageEditor メソッド。指定されたページのページサイズを返します。"
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

指定されたページのページサイズを返します。

```csharp
public PageSize GetPageSize(int page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | Int32 | ページインデックス。ドキュメントのページは 1 から番号付けされます。 |

### 戻り値

結果は PageSize のインスタンスです。返されたオブジェクトの Width と Height プロパティを使用して、ページの幅と高さを取得します。

## 例

以下の例は GetPageSize メソッドの使用例を示しています：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


