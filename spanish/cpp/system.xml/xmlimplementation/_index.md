---
title: "Clase System::Xml::XmlImplementation"
linktitle: "XmlImplementation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlImplementation. Define el contexto para un conjunto de objetos XmlDocument en C++."
type: docs
weight: 2000
url: /es/cpp/system.xml/xmlimplementation/
---
## XmlImplementation class


Define el contexto para un conjunto de objetos [XmlDocument](../xmldocument/).

```cpp
class XmlImplementation : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [CreateDocument](./createdocument/)() | Crea un nuevo [XmlDocument](../xmldocument/). |
| [HasFeature](./hasfeature/)(const String\&, const String\&) | Prueba si la implementación del Modelo de Objetos de Documento [Object](../../system/object/) (DOM) implementa una característica específica. |
| [XmlImplementation](./xmlimplementation/)() | Inicializa una nueva instancia de la clase [XmlImplementation](./). |
| [XmlImplementation](./xmlimplementation/)(const SharedPtr\<XmlNameTable\>\&) | Inicializa una nueva instancia de la clase [XmlImplementation](./) con la [XmlNameTable](../xmlnametable/) especificada. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
