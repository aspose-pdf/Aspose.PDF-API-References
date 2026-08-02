---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfXmpMetadata метод. Получает URI пространства имен по префиксу"
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method

Получает URI пространства имён по префиксу.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | String | Префикс. |

### Возвращаемое значение

URI пространства имён.

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### См. также

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


