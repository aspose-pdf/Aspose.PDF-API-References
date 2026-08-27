---
title: "Signature.Verify"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Signature メソッド。この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true を、そうでない場合は false を返します"
type: docs
weight: 170
url: /ja/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

この署名に関して文書を検証し、文書が有効な場合は true、そうでない場合は false を返します。

```csharp
public bool Verify()
```

### 戻り値

ドキュメントが有効な場合は true。

### 関連項目

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

この署名に関して文書を検証し、文書が有効な場合は true、そうでない場合は false を返します。

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| オプション | ValidationOptions | 検証オプション。 |
| validationResult | ValidationResult& | 証明書の検証結果。 |

### 戻り値

ドキュメントが有効な場合は true。

### 関連項目

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

この署名に関して文書を検証し、文書が有効な場合は true、そうでない場合は false を返します。検証は外部の公開鍵証明書を使用して実行されます。

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | 検証用の公開鍵証明書。 |
| オプション | ValidationOptions | 検証オプション。 |
| validationResult | ValidationResult& | 証明書の検証結果。 |

### 戻り値

ドキュメントが有効な場合は true。

### 関連項目

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


