---
title: "PdfXmpMetadata.Contains"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfXmpMetadata. Vérifie si le dictionnaire contient la clé spécifiée"
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Vérifie si le dictionnaire contient la clé spécifiée.

```csharp
public bool Contains(string key)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| clé | String | Clé qui sera vérifiée. |

### Valeur de retour

True - si le dictionnaire contient la clé spécifiée ; sinon, false.

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Voir aussi

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Vérifie si le dictionnaire contient la propriété spécifiée.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | DefaultMetadataProperties | Propriété qui sera vérifiée. |

### Valeur de retour

True - si le dictionnaire contient la propriété spécifiée ; sinon, false.

### Voir aussi

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | Paire clé-valeur. |

### Valeur de retour

true si cette paire a été trouvée.

### Voir aussi

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


