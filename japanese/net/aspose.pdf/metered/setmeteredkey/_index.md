---
title: "Metered.SetMeteredKey"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Metered メソッド。メーターの公開キーとプライベートキーを設定します。アプリケーション起動時にメーターライセンスを購入した場合、この API を通常通り呼び出すだけで十分です。ただし、常に消費データのアップロードに失敗し、24 時間を超えるとライセンスが評価ステータスに設定されます。このようなケースを回避するには、ライセンスステータスを定期的に確認し、評価ステータスの場合は再度この API を呼び出す必要があります。"
type: docs
weight: 30
url: /ja/net/aspose.pdf/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

メーターパブリックキーとプライベートキーを設定します。メータライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常はこれだけで十分です。ただし、消費データのアップロードが常に失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を防ぐために、ライセンスステータスを定期的に確認し、評価ステータスであれば再度この API を呼び出してください。

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| publicKey | String | 公開キー |
| privateKey | String | プライベートキー |

### 関連項目

* class [Metered](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


