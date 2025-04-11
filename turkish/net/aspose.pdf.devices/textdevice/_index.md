---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TextDevice sınıfı. PDF belge sayfalarını metne dönüştürmek için sınıfı temsil eder.
type: docs
weight: 3680
url: /tr/net/aspose.pdf.devices/textdevice/
---
## TextDevice sınıfı

PDF belge sayfalarını metne dönüştürmek için sınıfı temsil eder.

```csharp
public sealed class TextDevice : PageDevice
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Raw metin biçimlendirme modu ve Unicode metin kodlaması ile `TextDevice`'in yeni bir örneğini başlatır. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Belirtilen kodlama için `TextDevice`'in yeni bir örneğini başlatır. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Metin çıkarma seçenekleri ile `TextDevice`'in yeni bir örneğini başlatır. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Belirtilen kodlama ile metin çıkarma seçenekleri için `TextDevice`'in yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Çıkarılan metnin kodlamasını alır veya ayarlar. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Metin çıkarma seçeneklerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Sayfayı dönüştürür ve metin akışı olarak kaydeder. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Verilen sayfada bazı işlemler gerçekleştirir ve sonuçları dosyaya kaydeder. |

## Açıklamalar

`TextDevice` nesnesi temelde PDF sayfasından metin çıkarmak için kullanılır.

## Örnekler

Örnek, ilk PDF belge sayfasında metin çıkarmayı göstermektedir.

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

* sınıf [PageDevice](../pagedevice/)
* ad alanı [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../)