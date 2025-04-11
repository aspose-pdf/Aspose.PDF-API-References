---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: 文档方法。加密文档。然后调用保存以获取文档的加密版本
type: docs
weight: 620
url: /zh/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

加密文档。然后调用保存以获取文档的加密版本。

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | 字符串 | 用户密码。 |
| ownerPassword | 字符串 | 拥有者密码。 |
| privileges | DocumentPrivilege | 文档权限，详细信息请参见 [`Permissions`](../permissions/)。 |
| cryptoAlgorithm | CryptoAlgorithm | 加密算法，详细信息请参见 [`CryptoAlgorithm`](../cryptoalgorithm/)。 |
| usePdf20 | 布尔值 | 支持修订版 6（扩展 8）。 |

### 示例

以下示例演示如何使用 [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege) 加密 PDF 文件

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

### 另请参阅

* 类 [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* 枚举 [CryptoAlgorithm](../../cryptoalgorithm/)
* 类 [Document](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

加密文档。然后调用保存以获取文档的加密版本。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | 字符串 | 用户密码。 |
| ownerPassword | 字符串 | 拥有者密码。 |
| permissions | Permissions | 文档权限，详细信息请参见 [`Permissions`](../permissions/)。 |
| cryptoAlgorithm | CryptoAlgorithm | 加密算法，详细信息请参见 [`CryptoAlgorithm`](../cryptoalgorithm/)。 |

### 另请参阅

* 枚举 [Permissions](../../permissions/)
* 枚举 [CryptoAlgorithm](../../cryptoalgorithm/)
* 类 [Document](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

加密文档。然后调用保存以获取文档的加密版本。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | 字符串 | 用户密码。 |
| ownerPassword | 字符串 | 拥有者密码。 |
| permissions | Permissions | 文档权限，详细信息请参见 [`Permissions`](../permissions/)。 |
| cryptoAlgorithm | CryptoAlgorithm | 加密算法，详细信息请参见 [`CryptoAlgorithm`](../cryptoalgorithm/)。 |
| usePdf20 | 布尔值 | 支持修订版 6（扩展 8）。 |

### 另请参阅

* 枚举 [Permissions](../../permissions/)
* 枚举 [CryptoAlgorithm](../../cryptoalgorithm/)
* 类 [Document](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)