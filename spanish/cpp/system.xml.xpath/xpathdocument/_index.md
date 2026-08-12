---
title: "Clase System::Xml::XPath::XPathDocument"
linktitle: "XPathDocument"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XPath::XPathDocument. Proporciona una representación rápida, de solo lectura y en memoria de un documento XML mediante el modelo de datos XPath en C++."
type: docs
weight: 200
url: /es/cpp/system.xml.xpath/xpathdocument/
---
## XPathDocument class


Proporciona una representación rápida, de solo lectura y en memoria de un documento XML mediante el modelo de datos [XPath](../).

```cpp
class XPathDocument : public System::Xml::XPath::IXPathNavigable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CreateNavigator](./createnavigator/)() override | Inicializa un objeto de solo lectura [XPathNavigator](../xpathnavigator/) para navegar por los nodos en este [XPathDocument](./). |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&) | Inicializa una nueva instancia de la clase [XPathDocument](./) a partir de los datos XML contenidos en el objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&, XmlSpace) | Inicializa una nueva instancia de la clase [XPathDocument](./) a partir de los datos XML contenidos en el objeto [XmlReader](../../system.xml/xmlreader/) especificado con el manejo de espacios en blanco especificado. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::TextReader\>\&) | Inicializa una nueva instancia de la clase [XPathDocument](./) a partir de los datos XML que están contenidos en el objeto TextReader especificado. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::Stream\>\&) | Inicializa una nueva instancia de la clase [XPathDocument](./) a partir de los datos XML en el objeto Stream especificado. |
| [XPathDocument](./xpathdocument/)(const String\&) | Inicializa una nueva instancia de la clase [XPathDocument](./) a partir de los datos XML en el archivo especificado. |
| [XPathDocument](./xpathdocument/)(const String\&, XmlSpace) | Inicializa una nueva instancia de la clase [XPathDocument](./) a partir de los datos XML en el archivo especificado con el manejo de espacios en blanco especificado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [IXPathNavigable](../ixpathnavigable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
