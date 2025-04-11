---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Image sınıfı. Resmi temsil eder
type: docs
weight: 5860
url: /tr/net/aspose.pdf/image/
---
## Resim sınıfı

Resmi temsil eder.

```csharp
public sealed class Image : BaseParagraph
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Resim](image/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BitmapBilgisi](../../aspose.pdf/image/bitmapinfo/) { get; set; } | Sıkıştırılmamış resim baytlarını alır veya ayarlar. |
| [BitmapBoyutu](../../aspose.pdf/image/bitmapsize/) { get; } | Resim bitmap boyutunu alır. |
| [Dosya](../../aspose.pdf/image/file/) { get; set; } | Resim dosyasını alır veya ayarlar. |
| [DosyaTürü](../../aspose.pdf/image/filetype/) { get; set; } | Resim dosya türünü alır veya ayarlar. |
| [Yükseklik](../../aspose.pdf/image/fixheight/) { get; set; } | Resim yüksekliğini alır veya ayarlar. |
| [Genişlik](../../aspose.pdf/image/fixwidth/) { get; set; } | Resim genişliğini alır veya ayarlar. |
| sanal [YatayHizalama](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Paragrafın yatay hizalamasını alır veya ayarlar. |
| sanal [Bağlantı](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça bağlantısını alır veya ayarlar (pdf oluşturucu için). |
| [ResimÖlçeği](../../aspose.pdf/image/imagescale/) { get; set; } | Resim ölçeğini alır veya ayarlar. |
| [ResimAkışı](../../aspose.pdf/image/imagestream/) { get; set; } | Resim akışını alır veya ayarlar. |
| [ÇözünürlükUygula](../../aspose.pdf/image/isapplyresolution/) { get; set; } | Resmin oluşturma sırasında çözünürlük kullanıp kullanmadığını belirten bir bool değeri alır veya ayarlar. |
| [SiyahBeyaz](../../aspose.pdf/image/isblackwhite/) { get; set; } | Resmin siyah-beyaz olmasının zorunlu olup olmadığını belirten bir bool değeri alır veya ayarlar. CCITT altformatında TIFF resmi kullanılıyorsa, bu özellik true olarak ayarlanmalıdır. |
| [SütundakiİlkParagraf](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [SatırİçiParagraf](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [YeniSayfada](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [SonrakiyleBirlikteTut](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [Kenarlık](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenarlığı alır veya ayarlar (pdf oluşturma için) |
| [Başlık](../../aspose.pdf/image/title/) { get; set; } | Resmin başlığını belirten bir string değeri alır veya ayarlar. |
| sanal [DikeyHizalama](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| [ZIndeksi](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değeri alır veya ayarlar. Daha büyük ZIndeksi olan bir grafik, daha küçük ZIndeksi olan grafiğin üzerine yerleştirilecektir. ZIndeksi negatif olabilir. Negatif ZIndeksi olan bir grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Klone](../../aspose.pdf/image/clone/)() | Resmi klonlar. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Resim) | Resim için mime türünü döndürür. |

## Örnekler

Aşağıdaki örnek, resimleri (PNG, JPEG, GIF, BMP veya diğer resim formatları) bir PDF dosyasına dönüştürmenin nasıl yapılacağını göstermektedir.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your image (bmp, png, gif, jpeg, etc.) File.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Initialize empty PDF document
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Load sample image file
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Save output PDF document
	  pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir = "YOUR_DATA_DIRECTORY"

    ' The path to your image (bmp, png, gif, jpeg, etc.) File.
    Dim imageFile = Path.Combine(dataDir, "Image-to-PDF.png")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf")
 
    'Initialize empty PDF document
    Using pdfDocument As Document = New Document()
        pdfDocument.Pages.Add()
        Dim image As Image = New Image()
 
        ' Load sample image file
        image.File = imageFile
        pdfDocument.Pages(1).Paragraphs.Add(image)
 
        ' Save output PDF document
        pdfDocument.Save(pdfFile)
    End Using
```

### Ayrıca Bakınız

* sınıf [BaseParagraph](../baseparagraph/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)