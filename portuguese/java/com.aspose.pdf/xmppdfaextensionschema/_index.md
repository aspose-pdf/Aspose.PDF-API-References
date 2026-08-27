---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Referência da API Aspose.PDF para Java"
description: "Descreve o esquema de extensão XMP fornecido pelo PDF/A-1."
type: docs
weight: 5720
url: /pt/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

Descreve o esquema de extensão XMP fornecido pelo PDF/A-1.

## Campos

| Campo | Descrição |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | Prefixo padrão do namespace de extensão. |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | URI padrão do namespace de extensão. |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | Prefixo padrão do namespace de campo. |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | URI padrão do namespace de extensão. |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | Prefixo padrão do namespace de propriedade. |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | URI padrão do namespace de propriedade. |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | Prefixo padrão do namespace de esquema. |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | URI padrão do namespace de esquema. |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | URI padrão do namespace de valor. |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | Prefixo padrão do namespace de tipo de valor. |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | URI padrão do namespace rdf. |
| [RDF_PREFIX](#RDF_PREFIX) | Prefixo padrão do namespace rdf. |
| [XMLNS](#XMLNS) |  |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | Inicializa um novo objeto. |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | Adiciona um novo objeto ao esquema. |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | Determina se o objeto existe no esquema. |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | Cria o elemento XML de descrição para o bloco de valores de propriedades. |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | Cria o elemento XML de descrição para todos os esquemas. |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | Cria a lista de elementos de esquemas a partir da árvore XML. |
| [getDescription](#getDescription--) | Obtém a descrição do esquema. |
| [getObjects1](#getObjects1--) | Obtém a lista de objetos (propriedades, tipos de valor). |
| [getObjectsInternal](#getObjectsInternal--) | Obtém a lista de objetos (propriedades, tipos de valor). |
| [getProperty](#getProperty-java.lang.String-) | Retorna a propriedade PDF/A pelo seu nome. |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | Retorna o índice da propriedade com o nome fornecido. |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | Retorna o elemento xml (tag - li) que representa o esquema na árvore xml. |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | Obtém os valores das propriedades como representação de árvore xml. |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | Inicializa o valor da propriedade. |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | Determina se o valor do prefixo faz parte da extensão pdf-a. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | Remove o objeto do esquema. |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

Prefixo padrão do namespace de extensão.

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

URI padrão do namespace de extensão.

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

Prefixo padrão do namespace de campo.

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

URI padrão do namespace de extensão.

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

Prefixo padrão do namespace de propriedade.

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

URI padrão do namespace de propriedade.

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

Prefixo padrão do namespace de esquema.

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

URI padrão do namespace de esquema.

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

URI padrão do namespace de valor.

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

Prefixo padrão do namespace de tipo de valor.

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

URI padrão do namespace rdf.

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

Prefixo padrão do namespace rdf.

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
Inicializa um novo objeto.

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
Adiciona um novo objeto ao esquema.

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
Determina se o objeto existe no esquema.

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
Cria o elemento XML de descrição para o bloco de valores de propriedades.

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
Cria o elemento XML de descrição para todos os esquemas.

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
Cria a lista de elementos de esquemas a partir da árvore XML.

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

Obtém a descrição do esquema.

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

Obtém a lista de objetos (propriedades, tipos de valor).

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

Obtém a lista de objetos (propriedades, tipos de valor).

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
Retorna a propriedade PDF/A pelo seu nome.

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
Retorna o índice da propriedade com o nome fornecido.

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
Retorna o elemento xml (tag - li) que representa o esquema na árvore xml.

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
Obtém os valores das propriedades como representação de árvore xml.

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
Inicializa o valor da propriedade.

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
Determina se o valor do prefixo faz parte da extensão pdf-a.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
Remove o objeto do esquema.
