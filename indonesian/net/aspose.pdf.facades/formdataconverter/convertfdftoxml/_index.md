---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: Metode FormDataConverter. Mengonversi file FDF menjadi XML
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## Metode FormDataConverter.ConvertFdfToXml

Mengonversi file FDF menjadi XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceFdf | Stream | Stream yang berisi FDF untuk dikonversi. |
| destXml | Stream | Sumber tempat XML hasil akan ditempatkan. |

## Contoh

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### Lihat Juga

* kelas [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)