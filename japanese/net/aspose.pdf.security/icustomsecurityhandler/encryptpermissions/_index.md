---
title: "ICustomSecurityHandler.EncryptPermissions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ICustomSecurityHandler メソッド。ドキュメントの権限フィールドを暗号化します。結果は Perms 暗号化辞書フィールドに書き込まれます。ドキュメントを開く際、EncryptionParameters の Perms フィールドを通じて値を取得できます。ドキュメントの権限が変更されたかどうかを確認できます。"
type: docs
weight: 90
url: /ja/net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler.EncryptPermissions method

ドキュメントの権限フィールドを暗号化します。結果は Perms 暗号化辞書フィールドに書き込まれます。ドキュメントを開く際、[`EncryptionParameters`](../../encryptionparameters/) の Perms フィールドを通じて値を取得できます。ドキュメントの権限が変更されたかどうかを確認できます。

```csharp
public byte[] EncryptPermissions(int permissions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 権限 | Int32 | 整数表現のドキュメント権限です。 |

### 戻り値

暗号化された配列です。

### 関連項目

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


