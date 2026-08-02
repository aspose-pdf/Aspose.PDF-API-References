---
title: "FormDataConverter.ConvertFdfToXml"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormDataConverter. Преобразовать файл FDF в XML"
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml method

Преобразовать файл FDF в XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFdf | Stream | Поток, содержащий FDF для преобразования. |
| destXml | Stream | Источник, куда будет помещён результирующий XML. |

## Примеры

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### См. также

* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


