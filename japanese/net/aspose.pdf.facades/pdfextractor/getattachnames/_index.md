---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor メソッド。PDF ファイル内の添付ファイルのリストを返します。注意: このメソッドを使用する前に ExtractAttachments を呼び出す必要があります。
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames メソッド

PDF ファイル内の添付ファイルのリストを返します。注意: このメソッドを使用する前に ExtractAttachments を呼び出す必要があります。

```csharp
public IList<string> GetAttachNames()
```

### 戻り値

添付ファイルのリスト

## 例

例は、PDF ファイルから添付ファイル名を抽出する方法を示しています。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### 関連項目

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)