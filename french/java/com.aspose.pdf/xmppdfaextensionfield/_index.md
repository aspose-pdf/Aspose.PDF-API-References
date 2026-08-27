---
title: "XmpPdfAExtensionField"
linktitle: "XmpPdfAExtensionField"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Ce schéma décrit un champ dans un type structuré. Il est très similaire au schéma de type de valeur de propriété PDF/A, mais définit un champ dans une structure plutôt que dans une propriété. Schéma."
type: docs
weight: 5690
url: /fr/java/com.aspose.pdf/xmppdfaextensionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionField, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionField

```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

Ce schéma décrit un champ dans un type structuré. Il est très similaire au schéma PDF/A Property Value Type, mais définit un champ dans une structure au lieu d'une propriété. URI de l'espace de noms du schéma : http://www.aiim.org/pdfa/ns/field# Préfixe d'espace de noms requis pour le schéma : pdfaField.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpPdfAExtensionField](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initialise l'objet. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getName](#getName--) | Nom du champ. Les noms de champ doivent être des noms d'éléments XML valides. |
| [getValueType](#getValueType--) | Type de valeur du champ, tiré de la spécification XMP 2004, ou d'un schéma d'extension de type de valeur PDF/A intégré. Noms de type XMP prédéfinis ou noms de types personnalisés. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Renvoie la liste des éléments xml qui représentent le champ dans l'arbre xml. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Renvoie la liste des éléments xml qui représentent le champ dans l'arbre xml. |

### XmpPdfAExtensionField {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Initialise l'objet.

### getName {#getName--}
```
public String getName()
```

Nom du champ. Les noms de champ doivent être des noms d'éléments XML valides.

**Returns:**
Chaîne

### getValueType {#getValueType--}
```
public String getValueType()
```

Type de valeur du champ, tiré de la spécification XMP 2004, ou d'un schéma d'extension de type de valeur PDF/A intégré. Noms de type XMP prédéfinis ou noms de types personnalisés.

**Returns:**
Chaîne

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Renvoie la liste des éléments xml qui représentent le champ dans l'arbre xml.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Renvoie la liste des éléments xml qui représentent le champ dans l'arbre xml.
