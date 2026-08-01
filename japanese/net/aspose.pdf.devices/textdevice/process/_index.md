---
title: "TextDevice.Process"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextDevice メソッド。ページを変換し、テキストストリームとして保存します。"
type: docs
weight: 40
url: /ja/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

ページを変換し、テキストストリームとして保存します。

```csharp
public override void Process(Page page, Stream output)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | ページ | 変換するページです。 |
| output | Stream | 結果ストリームです。 |

## 例

この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // テキストデバイスを作成する
    TextDevice device = new TextDevice();

    // ページを変換し、テキストをストリームに保存する
    device.Process(doc.Pages[1], ms);

    // 抽出されたテキストを使用する
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


