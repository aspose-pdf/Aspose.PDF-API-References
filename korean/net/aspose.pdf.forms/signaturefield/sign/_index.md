---
title: SignatureField.Sign
second_title: Aspose.PDF for .NET API Reference
description: SignatureField 메서드. 이 서명 필드를 사용하여 문서에 서명합니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.forms/signaturefield/sign/
---
## Sign(Signature, Stream, string) {#sign_1}

이 서명 필드를 사용하여 문서에 서명합니다.

```csharp
public void Sign(Signature signature, Stream pfx, string pass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signature | Signature | 서명 객체, [`PKCS1`](../../pkcs1/), [`PKCS7`](../../pkcs7/), [`PKCS7Detached`](../../pkcs7detached/)를 참조하십시오. |
| pfx | Stream | 인증서가 포함된 스트림입니다. |
| pass | String | *pfx*의 개인 키에 접근하기 위한 비밀번호입니다. |

### See Also

* class [Signature](../../signature/)
* class [SignatureField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Sign(Signature) {#sign}

이 서명 필드를 사용하여 문서에 서명합니다.

```csharp
public void Sign(Signature signature)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signature | Signature | 서명 객체, [`PKCS1`](../../pkcs1/), [`PKCS7`](../../pkcs7/) 및 [`PKCS7Detached`](../../pkcs7detached/)를 참조하십시오. |

### See Also

* class [Signature](../../signature/)
* class [SignatureField](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)