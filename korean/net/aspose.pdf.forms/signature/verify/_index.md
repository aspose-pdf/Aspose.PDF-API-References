---
title: Signature.Verify
second_title: Aspose.PDF for .NET API Reference
description: 서명 방법. 이 서명에 대한 문서를 검증하고 문서가 유효하면 true를 반환하고 그렇지 않으면 false를 반환합니다.
type: docs
weight: 170
url: /ko/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

이 서명에 대한 문서를 검증하고 문서가 유효하면 true를 반환하고 그렇지 않으면 false를 반환합니다.

```csharp
public bool Verify()
```

### Return Value

문서가 유효하면 true입니다.

### See Also

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

이 서명에 대한 문서를 검증하고 문서가 유효하면 true를 반환하고 그렇지 않으면 false를 반환합니다.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ValidationOptions | 검증 옵션입니다. |
| validationResult | ValidationResult& | 인증서 검증 결과입니다. |

### Return Value

문서가 유효하면 true입니다.

### See Also

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)