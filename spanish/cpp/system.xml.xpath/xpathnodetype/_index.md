---
title: "System::Xml::XPath::XPathNodeType enum"
linktitle: "XPathNodeType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNodeType enum. Define los tipos de nodo XPath que pueden ser devueltos por la clase XPathNavigator en C++."
type: docs
weight: 1100
url: /es/cpp/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum


Define los tipos de nodo [XPath](../) que pueden ser devueltos por la clase [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Raíz | 0 | El nodo raíz del documento XML o del árbol de nodos. |
| Elemento | 1 | Un elemento, como **<element>**. |
| Atributo | 2 | Un atributo, como **id='123'**. |
| Espacio de nombres | 3 | Un espacio de nombres, como **xmlns=\"namespace\"**. |
| Text | 4 | El contenido de texto de un nodo. Equivalente al Modelo de Objeto de Documento (DOM) [Object](../../system/object/) [Text](../../system.text/) y a los tipos de nodo CDATA. Contiene al menos un carácter. |
| SignificantWhitespace | 5 | Un nodo con caracteres de espacio en blanco y **xml:space** establecido en **preserve**. |
| Whitespace | 6 | Un nodo con solo caracteres de espacio en blanco y sin espacio en blanco significativo. Los caracteres de espacio en blanco son **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Una instrucción de procesamiento, como **<?pi test?>**. Esto no incluye declaraciones XML, que no son visibles para la clase [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Un comentario, como ****. |
| All | 9 | Cualquiera de los tipos de nodo [XPathNodeType](./). |

## Ver también

* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
