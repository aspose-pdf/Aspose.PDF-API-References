---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfXmpMetadata. Obtém ou define valor por chave
type: docs
weight: 70
url: /pt/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## Indexador PdfXmpMetadata (1 de 2)

Obtém ou define valor por chave.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parâmetro | Descrição |
| --- | --- |
| key | O nome da chave para obter/definir. |

### Valor de Retorno

Objeto pela chave

## Exemplos

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Veja Também

* classe [XmpValue](../../../aspose.pdf/xmpvalue/)
* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Indexador PdfXmpMetadata (2 de 2)

Obtém valor dos metadados XMP pela chave.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parâmetro | Descrição |
| --- | --- |
| key | Chave do valor. |

### Valor de Retorno

Valor dos metadados XMP.

## Exemplos

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Veja Também

* classe [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)