---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Remove elemento com a chave especificada
type: docs
weight: 210
url: /pt/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Remove elemento com a chave especificada.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | DefaultMetadataProperties | Chave do elemento que será deletado. |

## Exemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### Veja Também

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Remove chave do dicionário.

```csharp
public bool Remove(string key)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | String | Chave que será removida. |

### Valor de Retorno

True - se a chave foi removida; caso contrário, false.

## Exemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### Veja Também

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Remove par chave/valor da coleção.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | KeyValuePair`2 | Par chave/valor a ser removido. |

### Valor de Retorno

true se o par foi encontrado e removido.

### Veja Também

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)