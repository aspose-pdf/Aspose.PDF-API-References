---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Verifica se o dicionário contém a chave especificada
type: docs
weight: 130
url: /pt/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Verifica se o dicionário contém a chave especificada.

```csharp
public bool Contains(string key)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | String | Chave que será verificada. |

### Valor de Retorno

True - se o dicionário contém a chave especificada; caso contrário, false.

## Exemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Veja Também

* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Verifica se o dicionário contém a propriedade especificada.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| property | DefaultMetadataProperties | Propriedade que será verificada. |

### Valor de Retorno

True - se o dicionário contém a propriedade especificada; caso contrário, false.

### Veja Também

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Verifica se o par chave-valor especificado está contido no dicionário.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | KeyValuePair`2 | Par chave-valor. |

### Valor de Retorno

true se este par foi encontrado.

### Veja Também

* classe [XmpValue](../../../aspose.pdf/xmpvalue/)
* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)