---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp プロパティ。入力ファイルの最初のページの開始番号を取得または設定します。次のページはこの値から番号が付けられます。たとえば、StartingNumber が 100 に設定されている場合、ドキュメントページには 100、101、102 の番号が付けられます。
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber プロパティ

入力ファイルの最初のページの開始番号を取得または設定します。次のページはこの値から番号が付けられます。たとえば、StartingNumber が 100 に設定されている場合、ドキュメントページには 100、101、102 の番号が付けられます...

```csharp
public int StartingNumber { get; set; }
```

## 例

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### 参照

* クラス [PdfFileStamp](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)