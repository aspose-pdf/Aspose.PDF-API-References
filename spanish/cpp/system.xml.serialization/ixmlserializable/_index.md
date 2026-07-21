---
title: "Clase System::Xml::Serialization::IXmlSerializable"
linktitle: "IXmlSerializable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Serialization::IXmlSerializable. Proporciona formato personalizado para la serialización y deserialización XML. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.xml.serialization/ixmlserializable/
---
## IXmlSerializable class


Proporciona formato personalizado para la serialización y deserialización XML. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class IXmlSerializable : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [GetSchema](./getschema/)() | Un objeto XmlSchema que describe la representación XML del objeto que es devuelto por el método [WriteXml()](./writexml/) y aceptado por el método [ReadXml()](./readxml/). |
| virtual [ReadXml](./readxml/)(System::SharedPtr\<System::Xml::XmlReader\>) | Deserializa el objeto a partir de su representación XML. |
| virtual [WriteXml](./writexml/)(System::SharedPtr\<System::Xml::XmlWriter\>) | Serializa el objeto actual a una representación XML. |
| virtual [~IXmlSerializable](./~ixmlserializable/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
