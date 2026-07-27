---
title: "XmpPdfAExtensionField"
linktitle: "XmpPdfAExtensionField"
second_title: "Referência da API Aspose.PDF para Java"
description: "Este esquema descreve um campo em um tipo estruturado. É muito semelhante ao esquema de Tipo de Valor de Propriedade PDF/A, mas define um campo em uma estrutura em vez de uma propriedade. Esquema."
type: docs
weight: 5690
url: /pt/java/com.aspose.pdf/xmppdfaextensionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionField, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionField

```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

Este esquema descreve um campo em um tipo estruturado. É muito semelhante ao esquema PDF/A Property Value Type, mas define um campo em uma estrutura em vez de uma propriedade. URI do namespace do esquema: http://www.aiim.org/pdfa/ns/field# Prefixo de namespace do esquema obrigatório: pdfaField.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XmpPdfAExtensionField](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Inicializa o objeto. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getName](#getName--) | Nome do campo. Os nomes de campo devem ser nomes de elementos XML válidos. |
| [getValueType](#getValueType--) | Tipo de valor do campo, extraído da Especificação XMP 2004, ou de um esquema de extensão de tipo de valor PDF/A incorporado. Nomes de tipo XMP predefinidos ou nomes de tipos personalizados. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Retorna a lista de elementos xml que representam o campo na árvore xml. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Retorna a lista de elementos xml que representam o campo na árvore xml. |

### XmpPdfAExtensionField {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Inicializa o objeto.

### getName {#getName--}
```
public String getName()
```

Nome do campo. Os nomes de campo devem ser nomes de elementos XML válidos.

**Returns:**
String

### getValueType {#getValueType--}
```
public String getValueType()
```

Tipo de valor do campo, extraído da Especificação XMP 2004, ou de um esquema de extensão de tipo de valor PDF/A incorporado. Nomes de tipo XMP predefinidos ou nomes de tipos personalizados.

**Returns:**
String

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Retorna a lista de elementos xml que representam o campo na árvore xml.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Retorna a lista de elementos xml que representam o campo na árvore xml.
