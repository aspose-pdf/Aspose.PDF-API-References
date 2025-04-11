---
title: Document.Decrypt
second_title: Aspose.PDF for .NET API Reference
description: Belge yöntemi. Belgeyi şifre çözme işlemi yapar. Şifrelenmemiş belge sürümünü elde etmek için ardından Kaydet'i çağırın.
type: docs
weight: 600
url: /tr/net/aspose.pdf/document/decrypt/
---
## Document.Decrypt yöntemi

Belgeyi şifre çözer. Şifrelenmemiş belge sürümünü elde etmek için ardından Kaydet'i çağırın.

```csharp
public void Decrypt()
```

### Örnekler

Aşağıdaki örnek kod, bir PDF dosyasını nasıl şifre çözeceğinizi göstermektedir.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document document = new Document(pdfFilePath, "YOUR_PASSWORD"))
	{
		// Decrypt PDF
		document.Decrypt();

		// Save updated PDF
		document.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"

    ' Open document
    Using document As Document = New Document(pdfFilePath, "YOUR_PASSWORD")

        ' Decrypt PDF
        document.Decrypt()

        ' Save updated PDF
        document.Save(pdfFilePath)
    End Using
```

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)