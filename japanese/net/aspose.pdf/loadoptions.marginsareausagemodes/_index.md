---
title: "列挙型 LoadOptions.MarginsAreaUsageModes"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.LoadOptionsMarginsAreaUsageModes 列挙型。HTML、EPUB などの変換時に余白領域の使用モードを表し、インポートされたフォーマットの余白使用に関する指示の取り扱いを定義します。"
type: docs
weight: 6270
url: /ja/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

変換時（HTML、EPUB など）の余白領域の使用モードを表し、インポートされたフォーマットの余白使用に関する指示の取り扱いを定義します。

```csharp
public enum MarginsAreaUsageModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | このモードでは、コンバータはインポートされた Document のフォーマット（例: インポートされた HTML の CSS）に従って余白領域を使用します。そのため、インポートされた Document のフォーマットがレンダリングに余白領域の使用を要求する場合、コンバータはそれを許可します。 |
| NeverPutContentOnMarginArea | `1` | このモードは余白領域の使用を厳格に禁止します。そのため、CSS やソース Document のフォーマットが許可または要求していても、コンバータは余白領域をレンダリングに使用しません。 |

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


