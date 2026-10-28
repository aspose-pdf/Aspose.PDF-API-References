---
title: "Document.Encrypt"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Document 메서드. 문서를 암호화합니다"
type: docs
weight: 640
url: /ko/net/aspose.pdf/document/encrypt/
---
## Encrypt(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) {#encrypt}

문서를 암호화합니다.

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| permissions | Permissions | Document 권한, 자세한 내용은 [`Permissions`](../permissions/)을(를) 확인하십시오. |
| cryptoAlgorithm | CryptoAlgorithm | 암호화 알고리즘, 자세한 내용은 [`CryptoAlgorithm`](../cryptoalgorithm/)을(를) 확인하십시오. |
| publicCertificates | IList`1 | 암호화에 사용되는 공개 인증서 — 수신자당 하나씩. |

## 비고

이 메서드는 암호화를 준비합니다. 문서를 암호화하려면 Save 메서드를 호출하여 저장해야 합니다.

### 또 보기

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

문서를 암호화합니다.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| privileges | DocumentPrivilege | Document 권한, 자세한 내용은 [`Permissions`](../permissions/)을(를) 확인하십시오. |
| customHandler | ICustomSecurityHandler | 사용자 지정 보안 처리기. |

## 비고

이 메서드는 암호화를 준비합니다. 문서를 암호화하려면 Save 메서드를 호출하여 저장해야 합니다.

### 또 보기

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

문서를 암호화합니다.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| permissions | Permissions | Document 권한, 자세한 내용은 [`Permissions`](../permissions/)을(를) 확인하십시오. |
| customHandler | ICustomSecurityHandler | 사용자 지정 보안 처리기. |

## 비고

이 메서드는 암호화를 준비합니다. 문서를 암호화하려면 Save 메서드를 호출하여 저장해야 합니다.

### 또 보기

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

문서를 암호화합니다.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| privileges | DocumentPrivilege | Document 권한, 자세한 내용은 [`Permissions`](../permissions/)을(를) 확인하십시오. |
| cryptoAlgorithm | CryptoAlgorithm | 암호화 알고리즘, 자세한 내용은 [`CryptoAlgorithm`](../cryptoalgorithm/)을(를) 확인하십시오. |
| usePdf20 | Boolean | 리비전 6 (Extension 8)을 지원합니다. |

## 비고

이 메서드는 암호화를 준비합니다. 문서를 암호화하려면 Save 메서드를 호출하여 저장해야 합니다.

### 또 보기

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

문서를 암호화합니다.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| permissions | Permissions | Document 권한, 자세한 내용은 [`Permissions`](../permissions/)을(를) 확인하십시오. |
| cryptoAlgorithm | CryptoAlgorithm | 암호화 알고리즘, 자세한 내용은 [`CryptoAlgorithm`](../cryptoalgorithm/)을(를) 확인하십시오. |

## 비고

이 메서드는 암호화를 준비합니다. 문서를 암호화하려면 Save 메서드를 호출하여 저장해야 합니다.

### 또 보기

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

문서를 암호화합니다.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| permissions | Permissions | Document 권한, 자세한 내용은 [`Permissions`](../permissions/)을(를) 확인하십시오. |
| cryptoAlgorithm | CryptoAlgorithm | 암호화 알고리즘, 자세한 내용은 [`CryptoAlgorithm`](../cryptoalgorithm/)을(를) 확인하십시오. |
| usePdf20 | Boolean | 리비전 6 (Extension 8)을 지원합니다. |

## 비고

이 메서드는 암호화를 준비합니다. 문서를 암호화하려면 Save 메서드를 호출하여 저장해야 합니다.

### 또 보기

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


