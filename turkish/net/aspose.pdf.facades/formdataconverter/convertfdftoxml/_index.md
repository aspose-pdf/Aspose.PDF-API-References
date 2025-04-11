---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter metodu. FDF dosyasını XML'e dönüştür
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml metodu

FDF dosyasını XML'e dönüştür.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFdf | Stream | Dönüştürülecek FDF'yi içeren akış. |
| destXml | Stream | Sonuç XML'in yerleştirileceği kaynak. |

## Örnekler

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### Ayrıca Bakınız

* sınıf [FormDataConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)