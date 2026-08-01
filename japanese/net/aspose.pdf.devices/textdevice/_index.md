---
title: "クラス TextDevice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Devices.TextDevice クラス。pdf ドキュメントのページをテキストに変換するクラスを表します。"
type: docs
weight: 3800
url: /ja/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

PDF ドキュメントのページをテキストに変換するクラスを表します。

```csharp
public sealed class TextDevice : PageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | `TextDevice` の新しいインスタンスを、Raw テキストフォーマットモードと Unicode テキストエンコーディングで初期化します。 |
| [TextDevice](textdevice/#constructor_3)(Encoding) | 指定されたエンコーディング用に `TextDevice` の新しいインスタンスを初期化します。 |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | `TextDevice` の新しいインスタンスをテキスト抽出オプションで初期化します。 |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | 指定されたエンコーディング用に、テキスト抽出オプションとともに `TextDevice` の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | 抽出されたテキストのエンコーディングを取得または設定します。 |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | テキスト抽出オプションを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | ページを変換し、テキストストリームとして保存します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページで何らかの操作を実行し、結果をファイルに保存します。 |

## 備考

`TextDevice` オブジェクトは基本的に pdf ページからテキストを抽出するために使用されます。

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

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


