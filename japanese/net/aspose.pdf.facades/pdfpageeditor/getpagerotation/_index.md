---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor メソッド。指定されたページの回転を返します
type: docs
weight: 140
url: /ja/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation メソッド

指定されたページの回転を返します。

```csharp
public int GetPageRotation(int page)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | ページインデックス。ドキュメントのページは1から番号が付けられます。 |

### 戻り値

度数でのページ回転。

## 例

以下の例は、ページの回転を取得する方法を示しています。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### 参照

* クラス [PdfPageEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)