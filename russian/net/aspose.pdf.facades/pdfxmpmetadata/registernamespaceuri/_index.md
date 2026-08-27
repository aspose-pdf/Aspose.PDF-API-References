---
title: "PdfXmpMetadata.RegisterNamespaceURI"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfXmpMetadata. Регистрирует URI пространства имён."
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

Регистрирует URI пространства имён.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | String | Префикс. |
| namespaceURI | String | URI пространства имён. |

## Примеры

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### См. также

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


