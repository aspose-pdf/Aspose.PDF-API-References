---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XmpPdfAExtensionValueType. Le schéma ValueType PDF/A est requis pour tous les types de valeurs de propriété qui ne sont pas définis dans la spécification XMP 2004, c'est-à-dire pour les types de valeurs en dehors de la liste suivante  - Types de tableau Alt, Bag, Seq - Types de valeurs de base  Boolean, Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Types de valeurs de gestion des médias  AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Type de valeur de travail de base  Job - Types de valeurs de schéma EXIF  Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI de l'espace de noms du schéma  http//www.aiim.org/pdfa/ns/type Préfixe d'espace de noms du schéma requis  pdfaType
type: docs
weight: 11490
url: /fr/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## Classe XmpPdfAExtensionValueType

Le schéma ValueType PDF/A est requis pour tous les types de valeurs de propriété qui ne sont pas définis dans la spécification XMP 2004, c'est-à-dire pour les types de valeurs en dehors de la liste suivante : - Types de tableau (ce sont des types conteneurs qui peuvent contenir un ou plusieurs champs) : Alt, Bag, Seq - Types de valeurs de base : Boolean, (ouvert et fermé) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Types de valeurs de gestion des médias : AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Type de valeur de travail de base : Job - Types de valeurs de schéma EXIF : Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI de l'espace de noms du schéma : http://www.aiim.org/pdfa/ns/type# Préfixe d'espace de noms du schéma requis : pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Initialise un nouvel objet. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Obtient la description. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Obtient la liste des champs. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Obtient l'URI de l'espace de noms. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Obtient le préfixe. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Obtient le type de valeur. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Obtient ou définit la valeur. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Ajoute un nouveau champ. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Ajoute la plage de champs. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Efface tous les champs. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Renvoie la liste des éléments xml qui représentent le type de valeur dans l'arbre xml. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Supprime le champ de la liste des champs. |

### Voir aussi

* classe [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)