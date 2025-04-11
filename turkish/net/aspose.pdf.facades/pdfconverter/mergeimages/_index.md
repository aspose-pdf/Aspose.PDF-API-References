---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter metodu. Görüntü akışlarının listesini tek bir görüntü akışı olarak birleştirir. Desteklenmeyen format çıkış akışı kullanıldığında, varsayılan olarak Jpeg ile kodlanmış Png/jpg/tiff çıkış formatları desteklenmektedir.
type: docs
weight: 180
url: /tr/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages metodu

Görüntü akışlarının listesini tek bir görüntü akışı olarak birleştirir. Desteklenmeyen format çıkış akışı kullanıldığında, varsayılan olarak Jpeg ile kodlanmış Png/jpg/tiff çıkış formatları desteklenmektedir.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputImagesStreams | List`1 | Birleştirilecek görüntü akışlarının listesi. |
| outputImageFormat | ImageFormat | Birleştirilmiş akış için görüntü çıkış formatı. |
| mergeMode | ImageMergeMode | Birleştirme modu. Png/Jpg formatları için kullanılır. |
| horizontal | Nullable`1 | Çıktı görüntü akışı için tuval genişliğini ayarlamak üzere yatay oran. Sadece ImageMergeMode.Center ile Png/Jpg formatları için kullanılır. |
| vertical | Nullable`1 | Çıktı görüntü akışı için tuval yüksekliğini ayarlamak üzere dikey oran. Sadece ImageMergeMode.Center ile Png/Jpg formatları için kullanılır. |

### Dönüş Değeri

Çıktı görüntü formatında kodlanmış görüntü akışı.

### Ayrıca Bakınız

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)