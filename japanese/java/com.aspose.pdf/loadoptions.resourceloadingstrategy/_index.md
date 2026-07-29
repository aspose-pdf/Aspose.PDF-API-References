---
title: "LoadOptions.ResourceLoadingStrategy"
linktitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "場合によっては、外部リソース（画像や CSS など）の内部ローダーの使用を回避し、要求されたリソースをどこかから取得するカスタムメソッドを提供する必要があります。"
type: docs
weight: 2830
url: /ja/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

場合によっては、外部リソース（画像や CSS など）の内部ローダーの使用を回避し、要求されたリソースを取得するカスタムメソッドを提供する必要があります。たとえば、クラウド上で Aspose.PDf を使用する際には参照ファイルへの直接アクセスが不可能であり、特別なメソッドにカスタムコードを入れて使用する必要があります。このデリゲートはそのようなカスタムメソッドのシグネチャを定義します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
