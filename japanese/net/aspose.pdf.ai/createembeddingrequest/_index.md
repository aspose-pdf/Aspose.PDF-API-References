---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateEmbeddingRequest クラス。Create Embeddings エンドポイントへのリクエストを表します。
type: docs
weight: 260
url: /ja/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest クラス

Create Embeddings エンドポイントへのリクエストを表します。

```csharp
public class CreateEmbeddingRequest
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | 結果の出力埋め込みが持つべき次元の数を取得または設定します。テキスト埋め込み-3以降のモデルでのみサポートされています。 |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | 埋め込みを返す形式を取得または設定します。float または base64 のいずれかです。 |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | 埋め込む入力テキストを取得または設定します。文字列またはトークンの配列としてエンコードされます。単一のリクエストで複数の入力を埋め込むには、文字列の配列またはトークンの配列の配列を渡します。入力はモデルの最大入力トークン（text-embedding-ada-002の場合は8192トークン）を超えてはならず、空の文字列であってはならず、配列は2048次元以下でなければなりません。 |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | 埋め込みを生成するモデルを取得または設定します。 |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | エンドユーザーを表す一意の識別子を取得または設定します。これにより、OpenAIが監視および悪用を検出するのに役立ちます。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)