---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextDevice プロパティ。テキスト抽出オプションを取得または設定します
type: docs
weight: 30
url: /ja/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions プロパティ

テキスト抽出オプションを取得または設定します。

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## 例

この例では、生の順序でテキストを抽出する方法を示します。

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### 関連項目

* クラス [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* クラス [TextDevice](../)
* 名前空間 [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* アセンブリ [Aspose.PDF](../../../)