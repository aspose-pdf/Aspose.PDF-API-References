---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Referência da API Aspose.PDF para Java"
description: "O esquema PDF/A ValueType é necessário para todos os tipos de valor de propriedade que não estão definidos na especificação XMP 2004, ou seja, para tipos de valor fora da lista a seguir: -."
type: docs
weight: 5740
url: /pt/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

O esquema PDF/A ValueType é necessário para todos os tipos de valor de propriedade que não estão definidos na especificação XMP 2004, ou seja, para tipos de valor fora da lista a seguir: - Tipos de array (são tipos contêiner que podem conter um ou mais campos): Alt, Bag, Seq - Tipos de valor básicos: Boolean, Choice (aberto e fechado), Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipos de valor de Gerenciamento de Mídia: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo de valor básico de Trabalho/Fluxo: Job - Tipos de valor do esquema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI do namespace do esquema: http://www.aiim.org/pdfa/ns/type# Prefixo de namespace do esquema obrigatório: pdfaType

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Inicializa um novo objeto. |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Adicionar novo campo. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | Adiciona o intervalo de campos. |
| [clear](#clear--) | Limpa todos os campos. |
| [getFields](#getFields--) | Obtém a lista de campos. |
| [getNamespaceUri](#getNamespaceUri--) | Obtém o URI do namespace. |
| [getPrefix](#getPrefix--) | Obtém o prefixo. |
| [getType](#getType--) | Obtém o tipo de valor. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Retorna a lista de elementos xml que representam o campo na árvore xml. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Retorna a lista de elementos xml que representam o tipo de valor na árvore xml. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Remove o campo da lista de campos. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Inicializa um novo objeto.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
Adicionar novo campo.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
Adiciona o intervalo de campos.

### clear {#clear--}
```
public void clear()
```

Limpa todos os campos.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

Obtém a lista de campos.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

Obtém o URI do namespace.

**Returns:**
String

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

Obtém o prefixo.

**Returns:**
String

### getType {#getType--}
```
public String getType()
```

Obtém o tipo de valor.

**Returns:**
String

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Retorna a lista de elementos xml que representam o campo na árvore xml.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Retorna a lista de elementos xml que representam o tipo de valor na árvore xml.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
Remove o campo da lista de campos.
