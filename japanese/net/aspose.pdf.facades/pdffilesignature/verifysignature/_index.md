---
title: "PdfFileSignature.VerifySignature"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSignature メソッド。署名の有効性を確認します。"
type: docs
weight: 320
url: /ja/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

署名の有効性をチェックします。

```csharp
public bool VerifySignature(SignatureName signName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |

### 戻り値

bool 型の結果を返します。

### 関連項目

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

署名の有効性をチェックします。

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |
| オプション | ValidationOptions | 検証オプション。 |
| validationResult | ValidationResult& | 証明書の検証結果。 |

### 戻り値

bool 型の結果を返します。

## 備考

このメソッドは、OCSP および/または CRL（証明書失効リスト）を使用して署名証明書の失効を確認できるようにします。このメソッドは証明書チェーンや有効性はチェックせず、エンド証明書が失効しているかどうかのみを確認します。

### 関連項目

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) {#verifysignature_3}

署名の有効性をチェックします。検証は外部の公開鍵証明書を使用して実行されます。

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |
| publicKeyCertificate | X509Certificate2 | 検証用の公開鍵証明書。 |
| オプション | ValidationOptions | 検証オプション。 |
| validationResult | ValidationResult& | 証明書の検証結果。 |

### 戻り値

bool 型の結果を返します。

## 備考

このメソッドは、OCSP および/または CRL（証明書失効リスト）を使用して署名証明書の失効を確認できるようにします。このメソッドは証明書チェーンや有効性はチェックせず、エンド証明書が失効しているかどうかのみを確認します。

### 関連項目

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2) {#verifysignature_2}

署名の有効性をチェックします。検証は外部の公開鍵証明書を使用して実行されます。

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |
| publicKeyCertificate | X509Certificate2 | 検証用の公開鍵証明書。 |

### 戻り値

bool 型の結果を返します。

### 関連項目

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


