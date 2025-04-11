---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TextDevice クラス。PDF ドキュメントのページをテキストに変換するためのクラスを表します。
type: docs
weight: 3680
url: /ja/net/aspose.pdf.devices/textdevice/
---
## TextDevice クラス

PDF ドキュメントのページをテキストに変換するためのクラスを表します。

```csharp
public sealed class TextDevice : PageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | 生のテキストフォーマットモードと Unicode テキストエンコーディングで `TextDevice` の新しいインスタンスを初期化します。 |
| [TextDevice](textdevice/#constructor_3)(Encoding) | 指定されたエンコーディングのために `TextDevice` の新しいインスタンスを初期化します。 |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | テキスト抽出オプションを使用して `TextDevice` の新しいインスタンスを初期化します。 |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | 指定されたエンコーディングとテキスト抽出オプションを使用して `TextDevice` の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | 抽出されたテキストのエンコーディングを取得または設定します。 |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | テキスト抽出オプションを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | ページを変換し、テキストストリームとして保存します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページに対していくつかの操作を実行し、結果をファイルに保存します。 |

## 備考

`TextDevice` オブジェクトは基本的に PDF ページからテキストを抽出するために使用されます。

## 例

この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。

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

* クラス [PageDevice](../pagedevice/)
* 名前空間 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* アセンブリ [Aspose.PDF](../../)