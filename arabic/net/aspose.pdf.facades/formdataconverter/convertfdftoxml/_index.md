---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormDataConverter. تحويل ملف FDF إلى XML
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## طريقة FormDataConverter.ConvertFdfToXml

تحويل ملف FDF إلى XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceFdf | Stream | التدفق الذي يحتوي على FDF للتحويل. |
| destXml | Stream | المصدر الذي سيتم وضع XML الناتج فيه. |

## أمثلة

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### انظر أيضًا

* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)