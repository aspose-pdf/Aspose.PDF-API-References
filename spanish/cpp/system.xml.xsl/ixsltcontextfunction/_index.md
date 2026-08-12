---
title: "Clase System::Xml::Xsl::IXsltContextFunction"
linktitle: "IXsltContextFunction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Xsl::IXsltContextFunction. Proporciona una interfaz a una función dada definida en la hoja de estilo Extensible Stylesheet Language for Transformations (XSLT) durante la ejecución en tiempo de ejecución en C++."
type: docs
weight: 100
url: /es/cpp/system.xml.xsl/ixsltcontextfunction/
---
## IXsltContextFunction class


Proporciona una interfaz a una función dada definida en la hoja de estilo del Extensible Stylesheet Language for Transformations (XSLT) durante la ejecución.

```cpp
class IXsltContextFunction : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_ArgTypes](./get_argtypes/)() | Devuelve los tipos del Lenguaje de Ruta XML ([XPath](../../system.xml.xpath/)) suministrados para la lista de argumentos de la función. Esta información puede usarse para descubrir la firma de la función, lo que permite diferenciar entre funciones sobrecargadas. |
| virtual [get_Maxargs](./get_maxargs/)() | Devuelve el número máximo de argumentos para la función. Esto permite al usuario diferenciar entre funciones sobrecargadas. |
| virtual [get_Minargs](./get_minargs/)() | Devuelve el número mínimo de argumentos para la función. Esto permite al usuario diferenciar entre funciones sobrecargadas. |
| virtual [get_ReturnType](./get_returntype/)() | Devuelve el XPathResultType que representa el tipo [XPath](../../system.xml.xpath/) devuelto por la función. |
| virtual [Invoke](./invoke/)(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) | Proporciona el método para invocar la función con los argumentos dados en el contexto especificado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
