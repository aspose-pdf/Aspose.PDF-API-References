---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature メソッド。署名の有効性を確認します
type: docs
weight: 310
url: /ja/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

署名の有効性を確認します。

```csharp
public bool VerifySignature(SignatureName signName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |

### 戻り値

bool 型の結果を返します。

### 参照

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

署名の有効性を確認します。

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |
| options | ValidationOptions | 検証オプション。 |
| validationResult | ValidationResult& | 証明書の検証結果。 |

### 戻り値

bool 型の結果を返します。

## 備考

このメソッドでは、OCSP および/または CRL (証明書失効リスト) を使用して署名証明書の失効を確認できます。このメソッドは証明書チェーンとその有効性を確認しませんが、エンド証明書が失効しているかどうかは確認します。

### 参照

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)