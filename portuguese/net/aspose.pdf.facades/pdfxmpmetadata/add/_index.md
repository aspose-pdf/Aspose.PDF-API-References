---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Adiciona valor aos metadados XMP
type: docs
weight: 110
url: /pt/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Adicionar(DefaultMetadataProperties, XmpValue) {#add}

Adiciona valor aos metadados XMP.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chave | DefaultMetadataProperties | O nome da chave. |
| valor | XmpValue | Valor que será adicionado. |

## Exemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Veja Também

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Adicionar(XmpPdfAExtensionObject, string, string, string) {#add_1}

Adiciona campo de extensão aos metadados.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | O objeto de extensão pdf a ser adicionado. |
| namespacePrefix | String | O prefixo do esquema. |
| namespaceUri | String | O URI do namespace do esquema. |
| schemaDescription | String | A descrição opcional do esquema. |

### Veja Também

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Adicionar(string, XmpValue) {#add_3}

Adiciona novo elemento ao objeto dicionário.

```csharp
public void Add(string key, XmpValue value)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chave | String | Chave do novo elemento. |
| valor | XmpValue | Valor do elemento. |

## Exemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Veja Também

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Adicionar(string, object) {#add_4}

Adiciona novo elemento ao objeto dicionário.

```csharp
public void Add(string key, object value)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chave | String | Chave do novo elemento. |
| valor | Object | Valor do elemento. |

### Veja Também

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Adicionar(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Adiciona par com chave e valor ao dicionário.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | KeyValuePair`2 | Item a ser adicionado. |

### Veja Também

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)