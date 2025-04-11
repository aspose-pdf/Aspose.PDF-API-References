---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントメソッド。ドキュメントを暗号化します。暗号化されたバージョンのドキュメントを取得するには、次に保存を呼び出します。
type: docs
weight: 620
url: /ja/net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

ドキュメントを暗号化します。暗号化されたバージョンのドキュメントを取得するには、次に保存を呼び出します。

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | オーナーパスワード。 |
| privileges | DocumentPrivilege | ドキュメントの権限、詳細については[`Permissions`](../permissions/)を参照してください。 |
| cryptoAlgorithm | CryptoAlgorithm | 暗号化アルゴリズム、詳細については[`CryptoAlgorithm`](../cryptoalgorithm/)を参照してください。 |
| usePdf20 | Boolean | 改訂6（拡張8）のサポート。 |

### 例

次の例は、[DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege)を使用してPDFファイルを暗号化する方法を示しています。

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

### 関連項目

* クラス [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* 列挙 [CryptoAlgorithm](../../cryptoalgorithm/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_1}

ドキュメントを暗号化します。暗号化されたバージョンのドキュメントを取得するには、次に保存を呼び出します。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | オーナーパスワード。 |
| permissions | Permissions | ドキュメントの権限、詳細については[`Permissions`](../permissions/)を参照してください。 |
| cryptoAlgorithm | CryptoAlgorithm | 暗号化アルゴリズム、詳細については[`CryptoAlgorithm`](../cryptoalgorithm/)を参照してください。 |

### 関連項目

* 列挙 [Permissions](../../permissions/)
* 列挙 [CryptoAlgorithm](../../cryptoalgorithm/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_2}

ドキュメントを暗号化します。暗号化されたバージョンのドキュメントを取得するには、次に保存を呼び出します。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | オーナーパスワード。 |
| permissions | Permissions | ドキュメントの権限、詳細については[`Permissions`](../permissions/)を参照してください。 |
| cryptoAlgorithm | CryptoAlgorithm | 暗号化アルゴリズム、詳細については[`CryptoAlgorithm`](../cryptoalgorithm/)を参照してください。 |
| usePdf20 | Boolean | 改訂6（拡張8）のサポート。 |

### 関連項目

* 列挙 [Permissions](../../permissions/)
* 列挙 [CryptoAlgorithm](../../cryptoalgorithm/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)