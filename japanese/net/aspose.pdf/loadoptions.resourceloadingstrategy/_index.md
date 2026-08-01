---
title: "デリゲート LoadOptions.ResourceLoadingStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "場合によっては、画像や CSS などの外部リソースの内部ローダーの使用を回避し、どこかから要求されたリソースを取得するカスタムメソッドを提供する必要があります。たとえば、クラウド上で Aspose.Pdf を使用する際には参照ファイルへの直接アクセスが不可能なため、特別なメソッドにカスタムコードを入れる必要があります。このデリゲートはそのようなカスタムメソッドのシグネチャを定義します"
type: docs
weight: 6300
url: /ja/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

場合によっては、外部リソース（画像や CSS など）の内部ローダーの使用を回避し、どこかから要求されたリソースを取得するカスタムメソッドを提供する必要があります。たとえば、クラウド上で Aspose.Pdf を使用する際には参照ファイルへの直接アクセスが不可能であり、特別なメソッドにカスタムコードを入れる必要があります。このデリゲートはそのようなカスタムメソッドのシグネチャを定義します

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| resourceURI | String | リソース URI。 |

### 戻り値

ResourceLoadingResult オブジェクト。

### 関連項目

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


