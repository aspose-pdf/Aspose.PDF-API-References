---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfXmpMetadata. Supprime l'élément avec la clé spécifiée
type: docs
weight: 210
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Supprime l'élément avec la clé spécifiée.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | Clé de l'élément qui sera supprimé. |

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### Voir aussi

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Supprime la clé du dictionnaire.

```csharp
public bool Remove(string key)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| key | String | Clé qui sera supprimée. |

### Valeur de retour

Vrai - si la clé a été supprimée ; sinon, faux.

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### Voir aussi

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Supprime la paire clé/valeur de la collection.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | Paire clé/valeur à supprimer. |

### Valeur de retour

vrai si la paire a été trouvée et supprimée.

### Voir aussi

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)