---
title: "TextDevice.ExtractionOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextDevice プロパティ。テキスト抽出オプションを取得または設定します"
type: docs
weight: 30
url: /ja/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

テキスト抽出オプションを取得または設定します。

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## 例

この例は、テキストを生の順序で抽出する方法を示しています。

```csharp
Document doc = new Document(inFile);
string extractedText;

// テキストデバイスを作成する
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// ページを変換し、テキストをストリームに保存する
device.Process(doc.Pages[1], outFile);

// 抽出されたテキストを使用する
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### 関連項目

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


