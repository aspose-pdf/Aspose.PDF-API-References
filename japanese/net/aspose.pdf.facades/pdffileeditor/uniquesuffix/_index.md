---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor プロパティ。フォームが連結されるときにフィールド名をユニークにするために追加されるサフィックスの形式。この文字列には、数字に置き換えられる NUM サブストリングを含める必要があります。たとえば、UniqueSuffix が ABCNUM の場合、フィールド名 fieldName の名前は fieldNameABC1、fieldNameABC2、fieldNameABC3 などになります。
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix プロパティ

フォームが連結されるときにフィールド名をユニークにするために追加されるサフィックスの形式。この文字列には、数字に置き換えられる %NUM% サブストリングを含める必要があります。たとえば、UniqueSuffix = "ABC%NUM%" の場合、フィールド "fieldName" の名前は次のようになります: fieldNameABC1、fieldNameABC2、fieldNameABC3 など。

```csharp
public string UniqueSuffix { get; set; }
```

## 例

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)