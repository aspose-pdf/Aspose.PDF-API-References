---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 時には、画像やCSSのような外部リソースの内部ローダーの使用を避け、要求されたリソースをどこかから取得するカスタムメソッドを提供する必要があります。たとえば、Aspose.Pdfをクラウドで使用する際には、参照されたファイルへの直接アクセスが不可能であり、特別なメソッドにカスタムコードを入れる必要があります。このデリゲートは、そのようなカスタムメソッドのシグネチャを定義します。
type: docs
weight: 6160
url: /ja/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy デリゲート

時には、画像やCSSのような外部リソースの内部ローダーの使用を避け、要求されたリソースをどこかから取得するカスタムメソッドを提供する必要があります。たとえば、Aspose.Pdfをクラウドで使用する際には、参照されたファイルへの直接アクセスが不可能であり、特別なメソッドにカスタムコードを入れる必要があります。このデリゲートは、そのようなカスタムメソッドのシグネチャを定義します。

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| resourceURI | 文字列 | リソースURI。 |

### 戻り値

ResourceLoadingResult オブジェクト。

### 参照

* クラス [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)