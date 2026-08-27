---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ValidationOptions プロパティ。検証プロセス中に証明書チェーンをチェックすべきかどうかを示す値を取得または設定します。"
type: docs
weight: 20
url: /ja/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

検証プロセス中に証明書チェーンをチェックすべきかどうかを示す値を取得または設定します。

```csharp
public bool CheckCertificateChain { get; set; }
```

## 備考

プロパティが設定されると、証明書チェーンの存在がチェックされます。チェーンが存在しない場合、検証結果は Undefined となり、これは Adobe Acrobat の動作に対応します。オンラインで失効ステータスのみを確認したい場合は、フィールドを `false` に設定してください。既定値は `false` です。

### 関連項目

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


