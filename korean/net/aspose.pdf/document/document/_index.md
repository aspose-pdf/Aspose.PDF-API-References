---
title: "Document.Document"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Document 생성자. 입력 스트림에서 새로운 Document 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

새로운 Document 인스턴스를 *input* 스트림에서 초기화합니다.

```csharp
public Document(Stream input)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 입력 | Stream | pdf 문서가 포함된 스트림. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_6}

새로운 Document 인스턴스를 *input* 스트림에서 초기화합니다.

```csharp
public Document(Stream input, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 입력 | Stream | pdf 문서가 포함된 스트림. |
| isManagedStream | Boolean | 만약 `true` 로 설정하면 내부 스트림이 종료 전에 닫힙니다; 그렇지 않으면 닫히지 않습니다. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_7}

새로운 Document 인스턴스를 *input* 스트림에서 초기화합니다.

```csharp
public Document(Stream input, string password)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 입력 | Stream | 입력 스트림 객체, 해당 pdf는 비밀번호로 보호됩니다. |
| password | String | 사용자 또는 소유자 비밀번호. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions) {#constructor_4}

새로운 Document 인스턴스를 *input* 스트림에서 초기화합니다.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 입력 | Stream | 입력 스트림 객체, 해당 pdf는 비밀번호로 보호됩니다. |
| certOptions | CertificateEncryptionOptions | 인증서 암호화 옵션. |

### 또 보기

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions, bool) {#constructor_5}

새로운 Document 인스턴스를 *input* 스트림에서 초기화합니다.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 입력 | Stream | pdf 문서가 포함된 스트림. |
| certOptions | CertificateEncryptionOptions | 인증서 암호화 옵션. |
| isManagedStream | Boolean | `true`로 설정하면 내부 스트림이 종료 전에 닫히고, 그렇지 않으면 닫히지 않습니다. |

### 또 보기

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions) {#constructor_13}

암호화된 문서를 작업하기 위해 [`Document`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | Document 파일 이름. |
| certOptions | CertificateEncryptionOptions | 인증서 암호화 옵션. |

### 또 보기

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions, bool) {#constructor_14}

암호화된 문서를 작업하기 위해 [`Document`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | Document 파일 이름. |
| certOptions | CertificateEncryptionOptions | 인증서 암호화 옵션. |
| isManagedStream | Boolean | 만약 `true` 로 설정하면 내부 스트림이 종료 전에 닫힙니다; 그렇지 않으면 닫히지 않습니다. |

### 또 보기

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, ICustomSecurityHandler) {#constructor_8}

새로운 Document 인스턴스를 *input* 스트림에서 초기화합니다.

```csharp
public Document(Stream input, string password, ICustomSecurityHandler customSecurityHandler)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 입력 | Stream | 입력 스트림 객체, 해당 pdf는 비밀번호로 보호됩니다. |
| password | String | 사용자 또는 소유자 비밀번호. |
| customSecurityHandler | ICustomSecurityHandler | 사용자 지정 보안 처리기. |

### 또 보기

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_9}

새로운 Document 인스턴스를 *input* 스트림에서 초기화합니다.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 입력 | Stream | pdf 문서가 포함된 스트림. |
| password | String | 사용자 또는 소유자 비밀번호. |
| isManagedStream | Boolean | `true`로 설정하면 내부 스트림이 종료 전에 닫히고, 그렇지 않으면 닫히지 않습니다. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool, ICustomSecurityHandler) {#constructor_10}

새로운 Document 인스턴스를 *input* 스트림에서 초기화합니다.

```csharp
public Document(Stream input, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 입력 | Stream | pdf 문서가 포함된 스트림. |
| password | String | 사용자 또는 소유자 비밀번호. |
| isManagedStream | Boolean | `true`로 설정하면 내부 스트림이 종료 전에 닫히고, 그렇지 않으면 닫히지 않습니다. |
| customSecurityHandler | ICustomSecurityHandler | 사용자 지정 보안 처리기. |

### 또 보기

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_11}

*filename*을 사용하여 Document를 초기화합니다. `Document`와 동일합니다.

```csharp
public Document(string filename)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | pdf 문서 파일의 이름. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_15}

*filename*을 사용하여 Document를 초기화합니다. `Document`와 동일합니다.

```csharp
public Document(string filename, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | pdf 문서 파일의 이름. |
| isManagedStream | Boolean | `true`로 설정하면 내부 스트림이 종료 전에 닫히고, 그렇지 않으면 닫히지 않습니다. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, ICustomSecurityHandler) {#constructor_17}

암호화된 문서를 작업하기 위해 [`Document`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Document(string filename, string password, ICustomSecurityHandler customSecurityHandler)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | Document 파일 이름. |
| password | String | 사용자 또는 소유자 비밀번호. |
| customSecurityHandler | ICustomSecurityHandler | 사용자 지정 보안 처리기. |

### 또 보기

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_16}

암호화된 문서를 작업하기 위해 [`Document`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Document(string filename, string password)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | Document 파일 이름. |
| password | String | 사용자 또는 소유자 비밀번호. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_18}

암호화된 문서를 작업하기 위해 [`Document`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | Document 파일 이름. |
| password | String | 사용자 또는 소유자 비밀번호. |
| isManagedStream | Boolean | 만약 `true` 로 설정하면 내부 스트림이 종료 전에 닫힙니다; 그렇지 않으면 닫히지 않습니다. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool, ICustomSecurityHandler) {#constructor_19}

암호화된 문서를 작업하기 위해 [`Document`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Document(string filename, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | Document 파일 이름. |
| password | String | 사용자 또는 소유자 비밀번호. |
| isManagedStream | Boolean | 만약 `true` 로 설정하면 내부 스트림이 종료 전에 닫힙니다; 그렇지 않으면 닫히지 않습니다. |
| customSecurityHandler | ICustomSecurityHandler | 사용자 지정 보안 처리기. |

### 또 보기

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

빈 문서를 초기화합니다.

```csharp
public Document()
```

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

버전으로 빈 문서를 초기화합니다.

```csharp
public Document(PdfVersion version)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 버전 | PdfVersion | PDF 버전입니다. |

### 또 보기

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_12}

파일에서 기존 문서를 열어 pdf 문서를 얻기 위해 필요한 변환 옵션을 제공합니다.

```csharp
public Document(string filename, LoadOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | pdf 문서로 변환할 입력 파일. |
| 옵션 | LoadOptions | *filename* 을 pdf 문서로 변환하기 위한 속성을 나타냅니다. |

### 또 보기

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

스트림에서 기존 문서를 열어 pdf 문서를 얻기 위해 필요한 변환을 제공합니다.

```csharp
public Document(Stream input, LoadOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 입력 | Stream | pdf 문서로 변환할 입력 스트림. |
| 옵션 | LoadOptions | pdf 문서로 변환하기 위한 *input* 의 속성을 나타냅니다. |

### 또 보기

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


