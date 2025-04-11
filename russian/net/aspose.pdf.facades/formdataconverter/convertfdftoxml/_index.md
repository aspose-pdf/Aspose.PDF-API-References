---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: Метод FormDataConverter. Преобразовать FDF файл в XML
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## Метод FormDataConverter.ConvertFdfToXml

Преобразовать FDF файл в XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFdf | Stream | Поток, содержащий FDF для преобразования. |
| destXml | Stream | Место, куда будет помещен результат XML. |

## Примеры

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### См. также

* класс [FormDataConverter](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)