---
title: Class ComHelper
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ComHelper クラス。COM クライアントが Aspose.Pdf にドキュメントをロードするためのメソッドを提供します。
type: docs
weight: 3130
url: /ja/net/aspose.pdf/comhelper/
---
## ComHelper クラス

COM クライアントが Aspose.Pdf にドキュメントをロードするためのメソッドを提供します。

```csharp
public class ComHelper
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ComHelper](comhelper/)() | デフォルトコンストラクター。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile)(string) | *filename* を使用してドキュメントを作成し、返します。 [`Document`](../document/document/) と同じです。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_1)(string, LoadOptions) | 必要な変換オプションを提供してファイルから既存のドキュメントを開き、PDF ドキュメントを取得します。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_2)(string, string) | 暗号化されたドキュメントを操作するための [`Document`](../document/) クラスの新しいインスタンスを初期化して返します。 |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_3)(string, string, bool) | 暗号化されたドキュメントを操作するための [`Document`](../document/) クラスの新しいインスタンスを初期化します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream)(Stream) | *input* ストリームから新しいドキュメントインスタンスを初期化して返します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_2)(Stream, bool) | *input* ストリームから新しいドキュメントインスタンスを初期化して返します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_1)(Stream, LoadOptions) | 必要な変換を提供してストリームから既存のドキュメントを開き、PDF ドキュメントを取得します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_3)(Stream, string) | *input* ストリームから新しいドキュメントインスタンスを初期化して返します。 |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_4)(Stream, string, bool) | *input* ストリームから新しいドキュメントインスタンスを初期化して返します。 |

## 備考

ComHelper クラスを使用して、ファイルまたはストリームからドキュメントを COM アプリケーションの Document オブジェクトにロードします。Document クラスは、新しいドキュメントを作成するためのデフォルトコンストラクターを提供し、ファイルまたはストリームからドキュメントをロードするためのオーバーロードされたコンストラクターも提供します。 .NET アプリケーションから Aspose.Words を使用している場合は、すべての Document コンストラクターを直接使用できますが、COM アプリケーションから Aspose.Pdf を使用している場合は、デフォルトの Document コンストラクターのみが利用可能です。

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)