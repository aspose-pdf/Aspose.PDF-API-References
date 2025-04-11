---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Метод документа. Шифрует документ. Затем вызовите Save, чтобы получить зашифрованную версию документа
type: docs
weight: 620
url: /ru/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Шифрует документ. Затем вызовите Save, чтобы получить зашифрованную версию документа.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| privileges | DocumentPrivilege | Разрешения документа, см. [`Permissions`](../permissions/) для получения подробностей. |
| cryptoAlgorithm | CryptoAlgorithm | Криптографический алгоритм, см. [`CryptoAlgorithm`](../cryptoalgorithm/) для получения подробностей. |
| usePdf20 | Boolean | Поддержка ревизии 6 (Расширение 8). |

### Примеры

Следующий пример показывает, как шифровать PDF-файлы с помощью [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)

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

### См. также

* класс [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* перечисление [CryptoAlgorithm](../../cryptoalgorithm/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Шифрует документ. Затем вызовите Save, чтобы получить зашифрованную версию документа.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| permissions | Permissions | Разрешения документа, см. [`Permissions`](../permissions/) для получения подробностей. |
| cryptoAlgorithm | CryptoAlgorithm | Криптографический алгоритм, см. [`CryptoAlgorithm`](../cryptoalgorithm/) для получения подробностей. |

### См. также

* перечисление [Permissions](../../permissions/)
* перечисление [CryptoAlgorithm](../../cryptoalgorithm/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Шифрует документ. Затем вызовите Save, чтобы получить зашифрованную версию документа.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| permissions | Permissions | Разрешения документа, см. [`Permissions`](../permissions/) для получения подробностей. |
| cryptoAlgorithm | CryptoAlgorithm | Криптографический алгоритм, см. [`CryptoAlgorithm`](../cryptoalgorithm/) для получения подробностей. |
| usePdf20 | Boolean | Поддержка ревизии 6 (Расширение 8). |

### См. также

* перечисление [Permissions](../../permissions/)
* перечисление [CryptoAlgorithm](../../cryptoalgorithm/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)