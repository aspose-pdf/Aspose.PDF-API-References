---
title: "PdfXmpMetadata.Add"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfXmpMetadata. Ajoute une valeur aux métadonnées XMP"
type: docs
weight: 110
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Ajoute une valeur aux métadonnées XMP.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| clé | DefaultMetadataProperties | Le nom de la clé. |
| valeur | XmpValue | Valeur qui sera ajoutée. |

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Voir aussi

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Ajoute un champ d'extension aux métadonnées.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | L'objet d'extension pdf à ajouter. |
| namespacePrefix | String | Le préfixe du schéma. |
| namespaceUri | String | L'uri de l'espace de noms du schéma. |
| schemaDescription | String | La description facultative du schéma. |

### Voir aussi

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

Ajoute un nouvel élément à l'objet dictionnaire.

```csharp
public void Add(string key, XmpValue value)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| clé | String | Clé du nouvel élément. |
| valeur | XmpValue | Valeur de l'élément. |

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Voir aussi

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

Ajoute un nouvel élément à l'objet dictionnaire.

```csharp
public void Add(string key, object value)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| clé | String | Clé du nouvel élément. |
| valeur | Objet | Valeur de l'élément. |

### Voir aussi

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Ajoute une paire clé-valeur dans le dictionnaire.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | Élément à ajouter. |

### Voir aussi

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


