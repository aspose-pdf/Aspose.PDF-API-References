---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: TextDevice メソッド。ページを変換し、テキストストリームとして保存します。
type: docs
weight: 40
url: /ja/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process メソッド

ページを変換し、テキストストリームとして保存します。

```csharp
public override void Process(Page page, Stream output)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | Page | 変換するページ。 |
| output | Stream | 結果のストリーム。 |

## 例

この例では、最初の PDF ドキュメントページからテキストを抽出する方法を示します。

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### 参照

* クラス [Page](../../../aspose.pdf/page/)
* クラス [TextDevice](../)
* 名前空間 [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* アセンブリ [Aspose.PDF](../../../)