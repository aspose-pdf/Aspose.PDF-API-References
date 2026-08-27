---
title: "ICustomSecurityHandler.Decrypt"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ICustomSecurityHandler メソッド。データ配列を復号化します。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.security/icustomsecurityhandler/decrypt/
---
## ICustomSecurityHandler.Decrypt method

データ配列を復号化します。

```csharp
public byte[] Decrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| data | Byte[] | 復号化するデータ。 |
| objectNumber | Int32 | 暗号化されたデータを含むオブジェクトの番号。 |
| generation | Int32 | オブジェクトの世代。 |
| キー | Byte[] | CalculateEncryptionKey メソッドで取得したキー |

### 戻り値

復号化されたデータです。

### 関連項目

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


