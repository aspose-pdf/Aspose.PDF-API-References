---
title: "PdfPageEditor.GetPageRotation"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfPageEditor メソッド。指定されたページの回転角度を返します。"
type: docs
weight: 140
url: /ja/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation method

指定されたページの回転を返します。

```csharp
public int GetPageRotation(int page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | Int32 | ページインデックス。ドキュメントのページは 1 から番号付けされます。 |

### 戻り値

ページの回転角度（度）。

## 例

以下の例はページの回転角度を取得する方法を示しています：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### 関連項目

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


