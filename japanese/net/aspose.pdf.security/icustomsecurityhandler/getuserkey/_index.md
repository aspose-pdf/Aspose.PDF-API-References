---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ICustomSecurityHandler メソッド。ユーザーのパスワードに基づいてエンコードされた配列を作成します。この値は通常、パスワードがユーザーまたはオーナーに属するかを確認し、暗号化キーを取得するために使用されます。暗号化中に呼び出され、暗号化辞書を準備および設定します。ドキュメント暗号化を呼び出す際に、ユーザー指定のパスワードが引数として渡されます。"
type: docs
weight: 110
url: /ja/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

ユーザーのパスワードに基づいてエンコードされた配列を作成します。この値は通常、パスワードがユーザーまたは所有者に属するかを確認し、暗号化キーを取得するために使用されます。暗号化中に呼び出され、暗号化辞書を準備および設定します。ドキュメント暗号化を呼び出す際に、ユーザー指定のパスワードが引数として渡されます。

```csharp
public byte[] GetUserKey(string userPassword)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワードです。 |

### 戻り値

ユーザーキーの配列です。

### 関連項目

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


