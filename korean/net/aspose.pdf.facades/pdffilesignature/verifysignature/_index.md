---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature 메서드. 서명의 유효성을 검사합니다.
type: docs
weight: 310
url: /ko/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

서명의 유효성을 검사합니다.

```csharp
public bool VerifySignature(SignatureName signName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| signName | SignatureName | 서명의 이름입니다. |

### 반환 값

bool 유형의 결과를 반환합니다.

### 참조

* 클래스 [SignatureName](../../signaturename/)
* 클래스 [PdfFileSignature](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

서명의 유효성을 검사합니다.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| signName | SignatureName | 서명의 이름입니다. |
| options | ValidationOptions | 검증 옵션입니다. |
| validationResult | ValidationResult& | 인증서 검증 결과입니다. |

### 반환 값

bool 유형의 결과를 반환합니다.

## 비고

이 메서드는 OCSP 및/또는 CRL(인증서 폐기 목록)을 사용하여 서명 인증서를 확인할 수 있습니다. 이 메서드는 인증서 체인과 그 유효성을 검사하지 않지만, 최종 인증서가 폐기되었는지 여부는 확인합니다.

### 참조

* 클래스 [SignatureName](../../signaturename/)
* 클래스 [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* 클래스 [ValidationResult](../../../aspose.pdf.security/validationresult/)
* 클래스 [PdfFileSignature](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)