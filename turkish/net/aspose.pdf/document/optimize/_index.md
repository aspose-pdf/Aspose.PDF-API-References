---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Belge yöntemi. İlk sayfayı mümkün olan en hızlı şekilde açmak için belgeyi lineerleştirir, bir sonraki sayfayı mümkün olan en hızlı şekilde görüntüler veya bir sonraki sayfaya bağlantı ile geçiş yapar, sayfa verileri yavaş bir kanaldan teslim edildiğinde sayfayı gelen verilerle kademeli olarak görüntüler, kullanıcı etkileşimine izin verir, örneğin bir bağlantıyı takip etmek gibi, tüm sayfa alınmadan ve görüntülenmeden önce bile gerçekleştirilebilir. Bu yöntemi çağırmak belgeyi aslında kaydetmez. Aksine, belge yalnızca optimize edilmiş bir yapıya sahip olacak şekilde hazırlanır, ardından optimize edilmiş belgeyi almak için Kaydet'i çağırın.
type: docs
weight: 750
url: /tr/net/aspose.pdf/document/optimize/
---
## Document.Optimize yöntemi

Belgeyi lineerleştirir - ilk sayfayı mümkün olan en hızlı şekilde açmak için; - bir sonraki sayfayı görüntülemek veya bir sonraki sayfaya bağlantı ile geçiş yapmak için mümkün olan en hızlı şekilde; - sayfa verileri yavaş bir kanaldan teslim edildiğinde sayfayı gelen verilerle kademeli olarak görüntülemek (en yararlı verileri önce göstermek); - kullanıcı etkileşimine izin vermek, örneğin bir bağlantıyı takip etmek gibi, tüm sayfa alınmadan ve görüntülenmeden önce bile gerçekleştirilebilir. Bu yöntemi çağırmak belgeyi aslında kaydetmez. Aksine, belge yalnızca optimize edilmiş bir yapıya sahip olacak şekilde hazırlanır, ardından optimize edilmiş belgeyi almak için Kaydet'i çağırın.

```csharp
public void Optimize()
```

### Örnekler

Aşağıdaki örnek, bir PDF belgesini web için nasıl optimize edeceğinizi göstermektedir.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimize for web
	pdfDocument.Optimize();

	// Save output document
	pdfDocument.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
	
    ' Open document
    Using pdfDocument As Document = New Document(pdfFilePath)

        ' Optimize for web
        pdfDocument.Optimize()

        ' Save output document
        pdfDocument.Save(pdfFilePath)
    End Using
```

### Ayrıca Bakınız

* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)