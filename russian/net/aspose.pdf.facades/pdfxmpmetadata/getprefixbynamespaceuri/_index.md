---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfXmpMetadata. Получает префикс по URI пространства имен
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## Метод PdfXmpMetadata.GetPrefixByNamespaceURI

Получает префикс по URI пространства имен.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceURI | String | URI пространства имен. |

### Возвращаемое значение

Значение префикса.

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### См. также

* класс [PdfXmpMetadata](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)