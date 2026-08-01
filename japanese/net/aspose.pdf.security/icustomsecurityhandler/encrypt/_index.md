---
title: "ICustomSecurityHandler.Encrypt"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ICustomSecurityHandler メソッド。データ配列を暗号化します。"
type: docs
weight: 80
url: /ja/net/aspose.pdf.security/icustomsecurityhandler/encrypt/
---
## ICustomSecurityHandler.Encrypt method

データ配列を暗号化します。

```csharp
public byte[] Encrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| data | Byte[] | 暗号化するデータ。 |
| objectNumber | Int32 | 暗号化されたデータを含むオブジェクトの番号。 |
| generation | Int32 | オブジェクトの世代。 |
| キー | Byte[] | CalculateEncryptionKey メソッドで取得したキー |

### 戻り値

暗号化されたデータ。

### 関連項目

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


