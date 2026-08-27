---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le schéma PDF/A ValueType est requis pour tous les types de valeur de propriété qui ne sont pas définis dans la spécification XMP 2004, c’est‑à‑dire pour les types de valeur en dehors de la liste suivante : -."
type: docs
weight: 5740
url: /fr/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

Le schéma PDF/A ValueType est requis pour tous les types de valeur de propriété qui ne sont pas définis dans la spécification XMP 2004, c’est‑à‑dire pour les types de valeur en dehors de la liste suivante : - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Basic Job/Workflow value type: Job - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI de l'espace de noms du schéma : http://www.aiim.org/pdfa/ns/type# Préfixe d'espace de noms requis pour le schéma : pdfaType

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initialise un nouvel objet. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Ajouter un nouveau champ. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | Ajoute la plage de champs. |
| [clear](#clear--) | Efface tous les champs. |
| [getFields](#getFields--) | Obtient la liste des champs. |
| [getNamespaceUri](#getNamespaceUri--) | Obtient l'URI de l'espace de noms. |
| [getPrefix](#getPrefix--) | Obtient le préfixe. |
| [getType](#getType--) | Obtient le type de valeur. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Renvoie la liste des éléments xml qui représentent le champ dans l'arbre xml. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Renvoie la liste des éléments xml qui représentent le type de valeur dans l'arbre xml. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Supprime le champ de la liste des champs. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Initialise un nouvel objet.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
Ajouter un nouveau champ.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
Ajoute la plage de champs.

### clear {#clear--}
```
public void clear()
```

Efface tous les champs.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

Obtient la liste des champs.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

Obtient l'URI de l'espace de noms.

**Returns:**
Chaîne

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

Obtient le préfixe.

**Returns:**
Chaîne

### getType {#getType--}
```
public String getType()
```

Obtient le type de valeur.

**Returns:**
Chaîne

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Renvoie la liste des éléments xml qui représentent le champ dans l'arbre xml.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Renvoie la liste des éléments xml qui représentent le type de valeur dans l'arbre xml.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
Supprime le champ de la liste des champs.
