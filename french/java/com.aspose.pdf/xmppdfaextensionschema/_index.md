---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Décrit le schéma d'extension XMP fourni par PDF/A-1."
type: docs
weight: 5720
url: /fr/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

Décrit le schéma d'extension XMP fourni par PDF/A-1.

## Champs

| Champ | Description |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | Préfixe d'espace de noms d'extension par défaut. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | URI d'espace de noms d'extension par défaut. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | Préfixe d'espace de noms de champ par défaut. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | URI d'espace de noms d'extension par défaut. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | Préfixe d'espace de noms de propriété par défaut. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | URI d'espace de noms de propriété par défaut. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | Préfixe d'espace de noms de schéma par défaut. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | URI d'espace de noms de schéma par défaut. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | URI d'espace de noms de valeur par défaut. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | Préfixe d'espace de noms du type de valeur par défaut. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | URI d'espace de noms rdf par défaut. |
| [RDF_PREFIX](#RDF_PREFIX) | Préfixe d'espace de noms rdf par défaut. |
| [XMLNS](#XMLNS) |  |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Initialise un nouvel objet. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Ajoute un nouvel objet dans le schéma. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Détermine si l'objet existe dans le schéma. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Crée l'élément XML de description pour le bloc des valeurs des propriétés. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Crée l'élément XML de description pour tous les schémas. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Crée la liste des éléments de schémas à partir de l'arbre XML. |
| [getDescription](#getDescription--) | Obtient la description du schéma. |
| [getObjects1](#getObjects1--) | Obtient la liste des objets (propriétés, types de valeur). |
| [getObjectsInternal](#getObjectsInternal--) | Obtient la liste des objets (propriétés, types de valeur). |
| [getProperty](#getProperty-java.lang.String-) | Renvoie la propriété PDF/A par son nom. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | Renvoie l'index de la propriété avec le nom donné. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Renvoie l'élément xml (balise - li) qui représente le schéma dans l'arbre xml. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Obtient les valeurs des propriétés sous forme de représentation d'arbre xml. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Initialise la valeur de la propriété. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | Détermine si la valeur du préfixe fait partie de l'extension pdf-a. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Supprime l'objet du schéma. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

Préfixe d'espace de noms d'extension par défaut.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

URI d'espace de noms d'extension par défaut.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

Préfixe d'espace de noms de champ par défaut.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

URI d'espace de noms d'extension par défaut.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

Préfixe d'espace de noms de propriété par défaut.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

URI d'espace de noms de propriété par défaut.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

Préfixe d'espace de noms de schéma par défaut.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

URI d'espace de noms de schéma par défaut.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

URI d'espace de noms de valeur par défaut.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

Préfixe d'espace de noms du type de valeur par défaut.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

URI d'espace de noms rdf par défaut.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

Préfixe d'espace de noms rdf par défaut.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
Initialise un nouvel objet.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
Ajoute un nouvel objet dans le schéma.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
Détermine si l'objet existe dans le schéma.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
Crée l'élément XML de description pour le bloc des valeurs des propriétés.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
Crée l'élément XML de description pour tous les schémas.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
Crée la liste des éléments de schémas à partir de l'arbre XML.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

Obtient la description du schéma.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

Obtient la liste des objets (propriétés, types de valeur).

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

Obtient la liste des objets (propriétés, types de valeur).

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
Renvoie la propriété PDF/A par son nom.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
Renvoie l'index de la propriété avec le nom donné.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
Renvoie l'élément xml (balise - li) qui représente le schéma dans l'arbre xml.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
Obtient les valeurs des propriétés sous forme de représentation d'arbre xml.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
Initialise la valeur de la propriété.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
Détermine si la valeur du préfixe fait partie de l'extension pdf-a.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
Supprime l'objet du schéma.
