---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Belge yöntemi. Belgeyi şifreler. Şifreli belge sürümünü almak için ardından Kaydet'i çağırın.
type: docs
weight: 620
url: /tr/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Belgeyi şifreler. Şifreli belge sürümünü almak için ardından Kaydet'i çağırın.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userPassword | String | Kullanıcı şifresi. |
| ownerPassword | String | Sahip şifresi. |
| privileges | DocumentPrivilege | Belge izinleri, ayrıntılar için [`Permissions`](../permissions/) sayfasına bakın. |
| cryptoAlgorithm | CryptoAlgorithm | Kriptografik algoritma, ayrıntılar için [`CryptoAlgorithm`](../cryptoalgorithm/) sayfasına bakın. |
| usePdf20 | Boolean | Revizyon 6 (Uzantı 8) desteği. |

### Örnekler

Aşağıdaki örnek, PDF dosyalarını [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege) ile nasıl şifreleyeceğinizi göstermektedir.

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

### Ayrıca Bakınız

* sınıf [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

Belgeyi şifreler. Şifreli belge sürümünü almak için ardından Kaydet'i çağırın.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userPassword | String | Kullanıcı şifresi. |
| ownerPassword | String | Sahip şifresi. |
| permissions | Permissions | Belge izinleri, ayrıntılar için [`Permissions`](../permissions/) sayfasına bakın. |
| cryptoAlgorithm | CryptoAlgorithm | Kriptografik algoritma, ayrıntılar için [`CryptoAlgorithm`](../cryptoalgorithm/) sayfasına bakın. |

### Ayrıca Bakınız

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

Belgeyi şifreler. Şifreli belge sürümünü almak için ardından Kaydet'i çağırın.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userPassword | String | Kullanıcı şifresi. |
| ownerPassword | String | Sahip şifresi. |
| permissions | Permissions | Belge izinleri, ayrıntılar için [`Permissions`](../permissions/) sayfasına bakın. |
| cryptoAlgorithm | CryptoAlgorithm | Kriptografik algoritma, ayrıntılar için [`CryptoAlgorithm`](../cryptoalgorithm/) sayfasına bakın. |
| usePdf20 | Boolean | Revizyon 6 (Uzantı 8) desteği. |

### Ayrıca Bakınız

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)