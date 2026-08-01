---
title: "クラス ComHelper"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.ComHelper クラス。COM クライアントがドキュメントを Aspose.Pdf にロードするためのメソッドを提供します。"
type: docs
weight: 3240
url: /ja/net/aspose.pdf/comhelper/
---
## ComHelper class

COM クライアントがドキュメントを Aspose.Pdf にロードするためのメソッドを提供します。

```csharp
public class ComHelper
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ComHelper](comhelper/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile)(string) | 単に *filename* を使用して Document を作成し、返します。[`Document`](../document/document/) と同じです。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_1)(string, LoadOptions) | 必要な変換オプションを提供して、ファイルから既存のドキュメントを開き、PDF ドキュメントを取得します。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_2)(string, string) | 暗号化されたドキュメントを操作するために、[`Document`](../document/) クラスの新しいインスタンスを初期化して返します。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_3)(string, string, bool) | 暗号化されたドキュメントを操作するために、[`Document`](../document/) クラスの新しいインスタンスを初期化します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream)(Stream) | *input* ストリームから新しい Document インスタンスを初期化して返します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_2)(Stream, bool) | *input* ストリームから新しい Document インスタンスを初期化して返します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_1)(Stream, LoadOptions) | 必要な変換を提供して、ストリームから既存のドキュメントを開き、PDF ドキュメントを取得して返します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_3)(Stream, string) | *input* ストリームから新しい Document インスタンスを初期化して返します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_4)(Stream, string, bool) | *input* ストリームから新しい Document インスタンスを初期化して返します。 |

## 備考

COM アプリケーションで、ComHelper クラスを使用してファイルまたはストリームからドキュメントを Document オブジェクトにロードします。Document クラスは新しいドキュメントを作成するためのデフォルトコンストラクタを提供し、さらにファイルやストリームからドキュメントをロードするためのオーバーロードされたコンストラクタも提供します。.NET アプリケーションで Aspose.Words を使用している場合、すべての Document コンストラクタを直接使用できますが、COM アプリケーションで Aspose.Pdf を使用している場合は、デフォルトの Document コンストラクタのみが利用可能です。

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


