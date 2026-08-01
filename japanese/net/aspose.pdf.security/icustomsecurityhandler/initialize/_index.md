---
title: "ICustomSecurityHandler.Initialize"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ICustomSecurityHandler メソッド。暗号化のために現在のインスタンスを初期化するために呼び出されます。暗号化時には、転送されたプロパティ ICustomSecurityHandler のデータで満たされ、暗号化辞書からドキュメントを開く際にも使用されます。新しい暗号化中にこのメソッドが呼び出された場合、UserKey と OwnerKey は null になります。"
type: docs
weight: 120
url: /ja/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

暗号化のために現在のインスタンスを初期化するために呼び出されます。暗号化時には、転送されたプロパティ [`ICustomSecurityHandler`](../) のデータで満たされ、暗号化辞書からドキュメントを開く際にも使用されます。新しい暗号化中にこのメソッドが呼び出された場合、[`UserKey`](../../encryptionparameters/userkey/) と [`OwnerKey`](../../encryptionparameters/ownerkey/) は null になります。

```csharp
public void Initialize(EncryptionParameters parameters)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| パラメータ | EncryptionParameters | 暗号化パラメータです。 |

### 関連項目

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


