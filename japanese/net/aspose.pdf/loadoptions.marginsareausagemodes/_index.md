---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsMarginsAreaUsageModes 列挙型。HTML、EPUB などの変換中にマージンエリアの使用モードを表し、マージンの使用に関連するインポート形式の指示の取り扱いを定義します。
type: docs
weight: 6130
url: /ja/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes 列挙型

変換中のマージンエリアの使用モードを表します（HTML、EPUB など）、マージンの使用に関連するインポート形式の指示の取り扱いを定義します。

```csharp
public enum MarginsAreaUsageModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | このモードでは、コンバータはインポートされたドキュメントの形式（例：インポートされた HTML の CSS）に従ってマージンエリアを使用します。したがって、インポートされたドキュメントの形式がレンダリングのためにマージンエリアの使用を要求する場合、コンバータはそれを許可します。 |
| NeverPutContentOnMarginArea | `1` | このモードでは、マージンエリアの使用が厳格に禁止されているため、コンバータはソースドキュメントの CSS や形式がそれを許可または要求しても、マージンエリアをレンダリングに使用することはありません。 |

### 参照

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)