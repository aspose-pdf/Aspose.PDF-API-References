---
title: Metered.SetMeteredKey
second_title: Aspose.PDF for .NET API Reference
description: Metered メソッド。メーター付きの公開鍵と秘密鍵を設定します。アプリケーションを開始する際にメーター付きライセンスを購入した場合、この API を呼び出す必要があります。通常、これで十分です。しかし、常に消費データのアップロードに失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。このような事態を避けるために、ライセンスのステータスを定期的に確認する必要があります。評価ステータスの場合は、この API を再度呼び出してください。
type: docs
weight: 30
url: /ja/net/aspose.pdf/metered/setmeteredkey/
---
## Metered.SetMeteredKey メソッド

メーター付きの公開鍵と秘密鍵を設定します。メーター付きライセンスを購入した場合、アプリケーションを開始する際にこの API を呼び出す必要があります。通常、これで十分です。しかし、常に消費データのアップロードに失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。このような事態を避けるために、ライセンスのステータスを定期的に確認する必要があります。評価ステータスの場合は、この API を再度呼び出してください。

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| publicKey | String | 公開鍵 |
| privateKey | String | 秘密鍵 |

### 参照

* クラス [Metered](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)