---
title: "PdfFileSignature.VerifySignature"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileSignature 메서드. 서명의 유효성을 확인합니다."
type: docs
weight: 320
url: /ko/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

서명의 유효성을 검사합니다.

```csharp
public bool VerifySignature(SignatureName signName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| signName | SignatureName | 서명의 이름. |

### 반환 값

bool 형식의 결과를 반환합니다.

### 또 보기

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

서명의 유효성을 검사합니다.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| signName | SignatureName | 서명의 이름. |
| 옵션 | ValidationOptions | 검증 옵션. |
| validationResult | ValidationResult& | 인증서 검증 결과. |

### 반환 값

bool 형식의 결과를 반환합니다.

## 비고

이 메서드는 서명 인증서를 OCSP 및/또는 CRL(인증서 폐기 목록)을 사용하여 폐기 여부를 확인할 수 있게 해줍니다. 이 메서드는 인증서 체인 및 유효성을 확인하지 않지만 최종 인증서가 폐기되었는지 여부는 확인합니다.

### 또 보기

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) {#verifysignature_3}

서명의 유효성을 검사합니다. 검증은 외부 공개 키 인증서를 사용하여 수행됩니다.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| signName | SignatureName | 서명의 이름. |
| publicKeyCertificate | X509Certificate2 | 검증을 위한 공개 키 인증서. |
| 옵션 | ValidationOptions | 검증 옵션. |
| validationResult | ValidationResult& | 인증서 검증 결과. |

### 반환 값

bool 형식의 결과를 반환합니다.

## 비고

이 메서드는 서명 인증서를 OCSP 및/또는 CRL(인증서 폐기 목록)을 사용하여 폐기 여부를 확인할 수 있게 해줍니다. 이 메서드는 인증서 체인 및 유효성을 확인하지 않지만 최종 인증서가 폐기되었는지 여부는 확인합니다.

### 또 보기

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2) {#verifysignature_2}

서명의 유효성을 검사합니다. 검증은 외부 공개 키 인증서를 사용하여 수행됩니다.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| signName | SignatureName | 서명의 이름. |
| publicKeyCertificate | X509Certificate2 | 검증을 위한 공개 키 인증서. |

### 반환 값

bool 형식의 결과를 반환합니다.

### 또 보기

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


