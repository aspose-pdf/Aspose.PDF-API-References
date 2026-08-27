---
title: "PdfFileEditor.UniqueSuffix"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor プロパティ。フォームが連結される際にフィールド名を一意にするために追加されるサフィックスの形式。この文字列は NUM サブストリングを含んでいる必要があり、数字に置き換えられます。例えば UniqueSuffix が ABCNUM の場合、フィールド fieldName の名前は fieldNameABC1、fieldNameABC2、fieldNameABC3 などになります。"
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

フォームが結合される際にフィールド名を一意にするために追加されるサフィックスの形式。この文字列は %NUM% サブストリングを含む必要があり、数字に置き換えられます。例えば UniqueSuffix = \"ABC%NUM%\" の場合、フィールド \"fieldName\" の名前は fieldNameABC1、fieldNameABC2、fieldNameABC3 などになります。

```csharp
public string UniqueSuffix { get; set; }
```

## 例

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


