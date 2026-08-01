---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileSignature 메서드. 서명의 단일 X.509 인증서를 추출합니다."
type: docs
weight: 310
url: /ko/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

서명의 단일 X.509 인증서를 추출합니다.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| signName | SignatureName | 서명의 이름. |
| 인증서 | X509Certificate2& | 인증서를 찾은 경우 X.509 단일 인증서 객체를 반환하고, 그렇지 않으면 null을 반환합니다. |

### 반환 값

인증서를 찾았습니다.

### 또 보기

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

서명의 단일 X.509 인증서를 스트림으로 추출합니다.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| signName | SignatureName | 서명의 이름. |
| stream | Stream& | 인증서를 찾은 경우 X.509 단일 인증서 스트림을 반환하고, 그렇지 않으면 null을 반환합니다. |

### 반환 값

인증서를 찾았습니다.

### 또 보기

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


