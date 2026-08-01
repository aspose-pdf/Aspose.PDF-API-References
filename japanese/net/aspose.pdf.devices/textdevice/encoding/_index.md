---
title: "TextDevice.Encoding"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextDevice プロパティ。抽出されたテキストのエンコーディングを取得または設定します"
type: docs
weight: 20
url: /ja/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

抽出されたテキストのエンコーディングを取得または設定します。

```csharp
public Encoding Encoding { get; set; }
```

## 例

この例は、抽出されたテキストを UTF-8 エンコーディングで表現する方法を示しています。

```csharp
Document doc = new Document(inFile);
string extractedText;

// テキストデバイスを作成する
TextDevice device = new TextDevice(Encoding.UTF8);

// ページを変換し、テキストをストリームに保存する
device.Process(doc.Pages[1], outFile);

// 抽出されたテキストを使用する
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### 関連項目

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


