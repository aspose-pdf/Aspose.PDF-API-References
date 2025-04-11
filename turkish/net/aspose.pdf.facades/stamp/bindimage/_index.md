---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Damga yöntemi. Görseli damga olarak ayarlar
type: docs
weight: 100
url: /tr/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Görseli damga olarak ayarlar.

```csharp
public void BindImage(string imageFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageFile | String | Görsel dosya adı ve yolu. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [Stamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Damga olarak kullanılacak görseli ayarlar.

```csharp
public void BindImage(Stream image)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | Stream | Görsel verilerini içeren akış. |

### Ayrıca Bakınız

* sınıf [Stamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)