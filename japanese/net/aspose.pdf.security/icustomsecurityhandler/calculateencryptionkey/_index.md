---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ICustomSecurityHandler メソッド。EncryptionKey を計算します。通常、キーは UserKey に基づいて計算されます。呼び出し時の現在のパラメータを含む EncryptionParams の値を使用できます。この値は Encrypt と Decrypt の key 引数として渡されます。"
type: docs
weight: 60
url: /ja/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

EncryptionKey を計算します。通常、キーは UserKey に基づいて計算されます。呼び出し時の現在のパラメータを含む EncryptionParams の値を使用できます。この値は [`Encrypt`](../encrypt/) と [`Decrypt`](../decrypt/) の key 引数として渡されます。

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| password | String | ユーザーが入力したパスワードです。 |

### 戻り値

暗号化キーの配列です。

### 関連項目

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


