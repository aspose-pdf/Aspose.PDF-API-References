---
title: "PdfFileStamp.StartingNumber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileStamp プロパティ。入力ファイルの最初のページの開始番号を取得または設定します。次のページはこの値から番号付けされます。たとえば StartingNumber を 100 に設定すると、ドキュメントのページは 100、101、102 の番号になります。"
type: docs
weight: 100
url: /ja/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

入力ファイルの最初のページの開始番号を取得または設定します。次のページはこの値から番号付けされます。例えば StartingNumber を 100 に設定すると、ドキュメントのページ番号は 100、101、102…となります。

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

### 関連項目

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


