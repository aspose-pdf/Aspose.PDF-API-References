---
title: "ExternalSignature.ExternalSignature"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "ExternalSignature 생성자. X509Certificate2를 사용하여 분리된 PKCS7 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트카드 토큰을 지원합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

X509Certificate2를 사용하여 분리된 PKCS#7 `(detached)` 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드 및 토큰을 지원합니다.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 인증서 | X509Certificate2 | 개인 키가 포함된 인증서. |

## 비고

다이제스트 알고리즘은 인증서 키 데이터에 따라 자동으로 선택됩니다.

### 또 보기

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

X509Certificate2를 사용하여 분리된 PKCS#7 `(detached)` 서명을 생성합니다. 내보낼 수 없는 개인 키가 있는 USB 스마트 카드 및 토큰을 지원합니다.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 인증서 | X509Certificate2 | 개인 키가 포함된 인증서. |
| digestHashAlgorithm | DigestHashAlgorithm | 문서를 서명하기 위한 다이제스트 알고리즘. |

### 또 보기

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

X509Certificate2를 사용하여 분리된 PKCS#7 서명을 생성합니다. 이는 내보낼 수 없는 개인 키가 있는 USB 스마트 카드와 토큰을 지원합니다.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 인증서 | X509Certificate2 | 개인 키가 포함된 인증서. |
| 분리된 | Boolean | 서명이 분리되어야 하면 true, 그렇지 않으면 false. |

## 비고

분리된 경우 false로 설정하면 다이제스트 알고리즘은 항상 `SHA1`이 됩니다. 그렇지 않으면 다이제스트 알고리즘은 인증서 키 데이터에 따라 자동으로 선택됩니다( Auto 참조 ).

### 또 보기

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

X509Certificate2를 base64 문자열로 사용하여 PKCS#7 서명을 생성합니다.

```csharp
public ExternalSignature(string base64, bool detached)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| base64 | String | X509Certificate2를 base64 문자열로. |
| 분리된 | Boolean | 서명이 분리되어야 하면 true, 그렇지 않으면 false. |

## 비고

분리된 경우 false로 설정하면 다이제스트 알고리즘은 항상 `SHA1`이 됩니다. 그렇지 않으면 다이제스트 알고리즘은 인증서 키 데이터에 따라 자동으로 선택됩니다( Auto 참조 ).

### 또 보기

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

X509Certificate2를 base64 문자열로 사용하여 PKCS#7 `(detached)` 서명을 생성합니다.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| base64 | String | X509Certificate2를 base64 문자열로. |
| digestHashAlgorithm | DigestHashAlgorithm | 문서를 서명하기 위한 다이제스트 알고리즘. |

### 또 보기

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


