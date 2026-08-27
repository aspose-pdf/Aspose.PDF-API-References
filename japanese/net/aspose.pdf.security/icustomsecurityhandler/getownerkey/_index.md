---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ICustomSecurityHandler メソッド。パスワードに基づいてエンコードされた配列を作成し、暗号化辞書の O フィールドに書き込みます。渡された引数のみに依存すべきです。このフィールドから所有者パスワードを使用してユーザーパスワードを計算できます。暗号化中に呼び出され、暗号化辞書を準備および設定します。この値は CalculateEncryptionKey で利用可能となり、UserKey からキーを取得します。ドキュメント暗号化を呼び出す際にユーザーが指定したパスワードが渡されます。パスワードは指定されない場合や、1 つだけ指定される場合があります。"
type: docs
weight: 100
url: /ja/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

パスワードに基づいてエンコードされた配列を作成し、暗号化辞書の O フィールドに書き込みます。渡された引数のみに依存すべきです。このフィールドから所有者パスワードを使用してユーザーパスワードを計算できます。暗号化中に呼び出され、暗号化辞書を準備および設定します。この値は [`CalculateEncryptionKey`](../calculateencryptionkey/) で利用可能となり、UserKey からキーを取得します。ドキュメント暗号化を呼び出す際にユーザーが指定したパスワードが渡されます。パスワードは指定されない場合や、1 つだけ指定される場合があります。

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワードです。 |
| ownerPassword | String | 所有者パスワードです。 |

### 戻り値

所有者キーの配列です。

### 関連項目

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


