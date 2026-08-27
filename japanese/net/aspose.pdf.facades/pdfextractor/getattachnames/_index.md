---
title: "PdfExtractor.GetAttachNames"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor メソッド。PDF ファイル内の添付ファイルのリストを返します。注意: ExtractAttachments はこのメソッドを使用する前に呼び出す必要があります。"
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

PDFファイル内の添付ファイル一覧を返します。注: このメソッドを使用する前にExtractAttachmentsを呼び出す必要があります。

```csharp
public IList<string> GetAttachNames()
```

### 戻り値

添付ファイルのリスト

## 例

例では、PDFファイルから添付ファイル名を抽出する方法を示します。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


