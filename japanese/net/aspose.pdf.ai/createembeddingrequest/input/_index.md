---
title: "CreateEmbeddingRequest.Input"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "CreateEmbeddingRequest プロパティ。埋め込み対象の入力テキストを文字列またはトークン配列として取得または設定します。単一のリクエストで複数の入力を埋め込むには、文字列の配列またはトークン配列の配列を渡します。入力はモデルの最大入力トークン数（textembeddingada002 の場合は 8192 トークン）を超えてはならず、空文字列にすることはできません。また、配列は 2048 次元以下である必要があります。"
type: docs
weight: 40
url: /ja/net/aspose.pdf.ai/createembeddingrequest/input/
---
## CreateEmbeddingRequest.Input property

埋め込む入力テキストを取得または設定します。文字列またはトークン配列としてエンコードされます。単一リクエストで複数の入力を埋め込むには、文字列の配列またはトークン配列の配列を渡します。入力はモデルの最大入力トークン数（text-embedding-ada-002 の場合は8192トークン）を超えてはならず、空文字列であってはならず、配列は2048次元以下である必要があります。

```csharp
public string Input { get; set; }
```

### 関連項目

* class [CreateEmbeddingRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


