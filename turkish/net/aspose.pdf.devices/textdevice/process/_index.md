---
title: Process
second_title: Aspose.PDF for .NET API Referansı
description: Sayfayı dönüştürün ve metin akışı olarak kaydedin.
type: docs
weight: 40
url: /tr/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

Sayfayı dönüştürün ve metin akışı olarak kaydedin.

```csharp
public override void Process(Page page, Stream output)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| page | Page | Dönüştürülecek sayfa. |
| output | Stream | Sonuç akışı. |

### Örnekler

Örnek, metnin ilk PDF belgesi sayfasından nasıl çıkarılacağını gösterir.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // metin aygıtı oluştur
    TextDevice device = new TextDevice();

    // sayfayı dönüştür ve metni akışa kaydet
    device.Process(doc.Pages[1], ms);

    // ayıklanan metni kullan
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Ayrıca bakınız

* class [Page](../../../aspose.pdf/page)
* class [TextDevice](../../textdevice)
* ad alanı [Aspose.Pdf.Devices](../../textdevice)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
