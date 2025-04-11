---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfXmpMetadata. Получает URI пространства имен по префиксу
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## Метод PdfXmpMetadata.GetNamespaceURIByPrefix

Получает URI пространства имен по префиксу.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | String | Префикс. |

### Возвращаемое значение

URI пространства имен.

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### См. также

* класс [PdfXmpMetadata](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)