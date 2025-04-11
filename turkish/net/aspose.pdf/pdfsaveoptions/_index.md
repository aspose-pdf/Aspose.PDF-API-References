---
title: Class PdfSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfSaveOptions sınıfı. Pdf formatına dışa aktarma için kaydetme seçenekleri
type: docs
weight: 8430
url: /tr/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions sınıfı

Pdf formatına dışa aktarma için kaydetme seçenekleri

```csharp
public class PdfSaveOptions : SaveOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Aps sayfaları hazırlanırken font gliflerinin önbelleğe alınıp alınmayacağını belirten boolean değeri alır veya ayarlar. Pdf'den diğer formatlara dönüşümün performansını artırır ancak bellek tüketimini artırır. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Belge yanıt olarak kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını belirten boolean değeri alır veya ayarlar. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Bilgisayarda mevcut olmayan fontlar için varsayılan olarak kullanılan font adı. PDF belgesi, belgede ve cihazda mevcut olmayan fontlar içeriyorsa, API bu fontları varsayılan font ile değiştirir (eğer [`DefaultFontName`](./defaultfontname/) ile belirtilen font cihazda bulunuyorsa) |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Veri kaydetme formatı. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Geçici dosyalar için yol. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Oluşan herhangi bir uyarıyı işlemek için geri çağırma. WarningHandler, devam etme veya iptal etme belirten ReturnAction enum öğesini döndürür. Devam etme varsayılan eylemdir ve kaydetme işlemi devam eder, ancak kullanıcı iptal etmeyi de döndürebilir; bu durumda kaydetme işlemi durmalıdır. |

## Örnekler

Aşağıdaki örnek, PDF kaydederken varsayılan font adını nasıl ayarlayacağınızı gösterir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Load an existing PDF document with missing font
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Specify Default Font Name
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### Ayrıca Bakınız

* sınıf [SaveOptions](../saveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)