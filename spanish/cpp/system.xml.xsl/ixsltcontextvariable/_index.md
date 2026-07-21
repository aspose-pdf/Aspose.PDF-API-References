---
title: "Clase System::Xml::Xsl::IXsltContextVariable"
linktitle: "IXsltContextVariable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Xsl::IXsltContextVariable. Proporciona una interfaz a una variable dada que está definida en la hoja de estilo durante la ejecución en tiempo de ejecución en C++."
type: docs
weight: 200
url: /es/cpp/system.xml.xsl/ixsltcontextvariable/
---
## IXsltContextVariable class


Proporciona una interfaz a una variable dada que está definida en la hoja de estilo durante la ejecución.

```cpp
class IXsltContextVariable : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XsltContext\>) | Evalúa la variable en tiempo de ejecución y devuelve un objeto que representa el valor de la variable. |
| virtual [get_IsLocal](./get_islocal/)() | Devuelve un valor que indica si la variable es local. |
| virtual [get_IsParam](./get_isparam/)() | Devuelve un valor que indica si la variable es un parámetro de Extensible Stylesheet Language Transformations (XSLT). Esto puede ser un parámetro de una hoja de estilo o una plantilla. |
| virtual [get_VariableType](./get_variabletype/)() | Devuelve el XPathResultType que representa el tipo del Lenguaje de Ruta XML ([XPath](../../system.xml.xpath/)) de la variable. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
