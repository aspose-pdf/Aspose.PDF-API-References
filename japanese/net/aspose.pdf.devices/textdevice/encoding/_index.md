---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: TextDevice プロパティ。抽出されたテキストのエンコーディングを取得または設定します
type: docs
weight: 20
url: /ja/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding プロパティ

抽出されたテキストのエンコーディングを取得または設定します。

```csharp
public Encoding Encoding { get; set; }
```

## 例

この例では、抽出されたテキストを UTF-8 エンコーディングで表現する方法を示します。

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(Encoding.UTF8);

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### 関連項目

* クラス [TextDevice](../)
* 名前空間 [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* アセンブリ [Aspose.PDF](../../../)