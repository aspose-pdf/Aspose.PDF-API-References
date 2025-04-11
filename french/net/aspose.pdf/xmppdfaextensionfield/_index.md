---
title: Class XmpPdfAExtensionField
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XmpPdfAExtensionField. Ce schéma décrit un champ dans un type structuré. Il est très similaire au schéma de type de valeur de propriété PDF/A, mais définit un champ dans une structure au lieu d'une propriété. URI de l'espace de noms du schéma http//www.aiim.org/pdfa/ns/field Préfixe d'espace de noms de schéma requis pdfaField
type: docs
weight: 11440
url: /fr/net/aspose.pdf/xmppdfaextensionfield/
---
## Classe XmpPdfAExtensionField

Ce schéma décrit un champ dans un type structuré. Il est très similaire au schéma de type de valeur de propriété PDF/A, mais définit un champ dans une structure au lieu d'une propriété. URI de l'espace de noms du schéma : http://www.aiim.org/pdfa/ns/field# Préfixe d'espace de noms de schéma requis : pdfaField.

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | Initialise l'objet. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Obtient la description. |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | Nom du champ. Les noms de champ doivent être des noms d'éléments XML valides. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Obtient ou définit la valeur. |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | Type de valeur du champ, tiré de la spécification XMP 2004, ou un schéma d'extension de type de valeur PDF/A intégré. Noms de types XMP prédéfinis ou noms de types personnalisés. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | Renvoie la liste des éléments xml qui représentent le champ dans l'arbre xml. |

### Voir aussi

* classe [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)