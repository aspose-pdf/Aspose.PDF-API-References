---
title: "System::Security::Cryptography::Xml::XmlDsigC14NTransform clase"
linktitle: "XmlDsigC14NTransform"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::Xml::XmlDsigC14NTransform clase. Representa la transformación de canonicalización XML C14N para una firma digital sin comentarios. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1400
url: /es/cpp/system.security.cryptography.xml/xmldsigc14ntransform/
---
## XmlDsigC14NTransform class


Representa la transformación de canonicalización XML C14N para una firma digital sin comentarios. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class XmlDsigC14NTransform : public System::Security::Cryptography::Xml::Transform
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_InputTypes](./get_inputtypes/)() override |  |
| [get_OutputTypes](./get_outputtypes/)() override |  |
| [GetDigestedOutput](./getdigestedoutput/)(SharedPtr\<HashAlgorithm\>) override |  |
| [GetOutput](./getoutput/)() override |  |
| [GetOutput](./getoutput/)(const TypeInfo\&) override |  |
| [LoadInnerXml](./loadinnerxml/)(SharedPtr\<System::Xml::XmlNodeList\>) override |  |
| [LoadInput](./loadinput/)(SharedPtr\<Object\>) override |  |
| [XmlDsigC14NTransform](./xmldsigc14ntransform/)() |  |
| [XmlDsigC14NTransform](./xmldsigc14ntransform/)(bool) |  |
## Ver también

* Class [Transform](../transform/)
* Namespace [System::Security::Cryptography::Xml](../)
* Library [Aspose.PDF for C++](../../)
