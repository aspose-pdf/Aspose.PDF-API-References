---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: ExternalSignature 생성자. X509Certificate2를 사용하여 분리된 PKCS7 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 usb 스마트 카드 토큰을 지원합니다.
type: docs
weight: 10
url: /ko/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

X509Certificate2를 사용하여 분리된 PKCS#7 `(detached)` 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 usb 스마트 카드, 토큰을 지원합니다.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | 개인 키가 포함된 인증서입니다. |

## Remarks

다이제스트 알고리즘은 인증서 키 데이터에 따라 자동으로 선택됩니다.

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

X509Certificate2를 사용하여 분리된 PKCS#7 `(detached)` 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 usb 스마트 카드, 토큰을 지원합니다.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | 개인 키가 포함된 인증서입니다. |
| digestHashAlgorithm | DigestHashAlgorithm | 문서에 서명할 다이제스트 알고리즘입니다. |

### See Also

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

X509Certificate2를 사용하여 분리된 PKCS#7 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 usb 스마트 카드, 토큰을 지원합니다.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | 개인 키가 포함된 인증서입니다. |
| detached | Boolean | 서명이 분리되어야 하면 true, 그렇지 않으면 false입니다. |

## Remarks

detached가 false로 설정된 경우 다이제스트 알고리즘은 항상 `SHA1`이 됩니다. 그렇지 않으면 다이제스트 알고리즘은 인증서 키 데이터에 따라 자동으로 선택됩니다( Auto 참조 ).

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

base64 문자열로 X509Certificate2를 사용하여 PKCS#7 서명을 생성합니다.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| base64 | String | base64 문자열로 된 X509Certificate2입니다. |
| detached | Boolean | 서명이 분리되어야 하면 true, 그렇지 않으면 false입니다. |

## Remarks

detached가 false로 설정된 경우 다이제스트 알고리즘은 항상 `SHA1`이 됩니다. 그렇지 않으면 다이제스트 알고리즘은 인증서 키 데이터에 따라 자동으로 선택됩니다( Auto 참조 ).

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

base64 문자열로 X509Certificate2를 사용하여 PKCS#7 `(detached)` 서명을 생성합니다.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| base64 | String | base64 문자열로 된 X509Certificate2입니다. |
| digestHashAlgorithm | DigestHashAlgorithm | 문서에 서명할 다이제스트 알고리즘입니다. |

### See Also

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)