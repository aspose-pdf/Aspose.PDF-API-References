---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfXmpMetadata. Регистрирует URI пространства имен
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## Метод PdfXmpMetadata.RegisterNamespaceURI

Регистрирует URI пространства имен.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | String | Префикс. |
| namespaceURI | String | URI пространства имен. |

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### См. также

* класс [PdfXmpMetadata](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)