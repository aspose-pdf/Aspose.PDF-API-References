---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfXmpMetadata. Получает префикс по URI пространства имён"
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

Получает префикс по URI пространства имён.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceURI | String | URI пространства имён. |

### Возвращаемое значение

Значение префикса.

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### См. также

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


