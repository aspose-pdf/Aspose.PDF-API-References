---
title: "Signature.Verify"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Signature 메서드. 이 서명에 대해 문서를 검증하고, 문서가 유효하면 true를, 그렇지 않으면 false를 반환합니다."
type: docs
weight: 170
url: /ko/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

이 서명에 대해 문서를 검증하고, 문서가 유효하면 true, 그렇지 않으면 false를 반환합니다.

```csharp
public bool Verify()
```

### 반환 값

문서가 유효하면 true.

### 또 보기

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

이 서명에 대해 문서를 검증하고, 문서가 유효하면 true, 그렇지 않으면 false를 반환합니다.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 옵션 | ValidationOptions | 검증 옵션. |
| validationResult | ValidationResult& | 인증서 검증 결과. |

### 반환 값

문서가 유효하면 true.

### 또 보기

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

이 서명에 대해 문서를 검증하고, 문서가 유효하면 true, 그렇지 않으면 false를 반환합니다. 검증은 외부 공개 키 인증서를 사용하여 수행됩니다.

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | 검증을 위한 공개 키 인증서. |
| 옵션 | ValidationOptions | 검증 옵션. |
| validationResult | ValidationResult& | 인증서 검증 결과. |

### 반환 값

문서가 유효하면 true.

### 또 보기

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


