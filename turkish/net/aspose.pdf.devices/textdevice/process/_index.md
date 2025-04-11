---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: TextDevice metodu. Sayfayı dönüştür ve metin akışı olarak kaydet
type: docs
weight: 40
url: /tr/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process metodu

Sayfayı dönüştür ve metin akışı olarak kaydet.

```csharp
public override void Process(Page page, Stream output)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | Sayfa | Dönüştürülecek sayfa. |
| output | Akış | Sonuç akışı. |

## Örnekler

Örnek, ilk PDF belgesi sayfasındaki metni nasıl çıkaracağınızı gösterir.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Ayrıca Bakınız

* sınıf [Page](../../../aspose.pdf/page/)
* sınıf [TextDevice](../)
* ad alanı [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../../)