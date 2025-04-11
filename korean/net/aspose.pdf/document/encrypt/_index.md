---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: 문서 메서드. 문서를 암호화합니다. 암호화된 버전의 문서를 얻으려면 저장을 호출하십시오.
type: docs
weight: 620
url: /ko/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

문서를 암호화합니다. 암호화된 버전의 문서를 얻으려면 저장을 호출하십시오.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| privileges | DocumentPrivilege | 문서 권한, 자세한 내용은 [`Permissions`](../permissions/)를 참조하십시오. |
| cryptoAlgorithm | CryptoAlgorithm | 암호화 알고리즘, 자세한 내용은 [`CryptoAlgorithm`](../cryptoalgorithm/)를 참조하십시오. |
| usePdf20 | Boolean | 수정 6 (확장 8)에 대한 지원. |

### 예제

다음 예제는 [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)를 사용하여 PDF 파일을 암호화하는 방법을 보여줍니다.

```csharp
[C#]

	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document document = new Document(pdfFilePath))
	{
	// Encrypt PDF
	document.Encrypt("YOUR_USER_PASSWORD", "YOUR_OWNER_PASSWORD", DocumentPrivilege.AllowAll, CryptoAlgorithm.RC4x128, true);

	// Save updated PDF
	document.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
    
	' Open document
    Using document As Document = New Document(pdfFilePath)
        ' Encrypt PDF
        document.Encrypt("YOUR_USER_PASSWORD", "YOUR_OWNER_PASSWORD", DocumentPrivilege.AllowAll, CryptoAlgorithm.RC4x128, True)
        ' Save updated PDF
        document.Save(pdfFilePath)
    End Using
```

### 참조

* 클래스 [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* 열거형 [CryptoAlgorithm](../../cryptoalgorithm/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

문서를 암호화합니다. 암호화된 버전의 문서를 얻으려면 저장을 호출하십시오.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| permissions | Permissions | 문서 권한, 자세한 내용은 [`Permissions`](../permissions/)를 참조하십시오. |
| cryptoAlgorithm | CryptoAlgorithm | 암호화 알고리즘, 자세한 내용은 [`CryptoAlgorithm`](../cryptoalgorithm/)를 참조하십시오. |

### 참조

* 열거형 [Permissions](../../permissions/)
* 열거형 [CryptoAlgorithm](../../cryptoalgorithm/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

문서를 암호화합니다. 암호화된 버전의 문서를 얻으려면 저장을 호출하십시오.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| permissions | Permissions | 문서 권한, 자세한 내용은 [`Permissions`](../permissions/)를 참조하십시오. |
| cryptoAlgorithm | CryptoAlgorithm | 암호화 알고리즘, 자세한 내용은 [`CryptoAlgorithm`](../cryptoalgorithm/)를 참조하십시오. |
| usePdf20 | Boolean | 수정 6 (확장 8)에 대한 지원. |

### 참조

* 열거형 [Permissions](../../permissions/)
* 열거형 [CryptoAlgorithm](../../cryptoalgorithm/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)