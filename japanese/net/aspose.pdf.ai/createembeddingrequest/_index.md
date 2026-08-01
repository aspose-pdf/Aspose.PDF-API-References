---
title: "クラス CreateEmbeddingRequest"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.CreateEmbeddingRequest クラス。Create Embeddings エンドポイントへのリクエストを表します"
type: docs
weight: 270
url: /ja/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

Embeddings 作成エンドポイントへのリクエストを表します。

```csharp
public class CreateEmbeddingRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | 結果の出力埋め込みが持つべき次元数を取得または設定します。text-embedding-3 以降のモデルでのみサポートされます。 |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | 埋め込みを返す形式を取得または設定します。float または base64 のいずれかを指定できます。 |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | 埋め込む入力テキストを取得または設定します。文字列またはトークン配列としてエンコードされます。単一リクエストで複数の入力を埋め込むには、文字列の配列またはトークン配列の配列を渡します。入力はモデルの最大入力トークン数（text-embedding-ada-002 の場合は8192トークン）を超えてはならず、空文字列であってはならず、配列は2048次元以下である必要があります。 |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | 埋め込みを生成するモデルを取得または設定します。 |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | エンドユーザーを表す一意の識別子を取得または設定します。これにより OpenAI が濫用を監視・検出するのに役立ちます。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


