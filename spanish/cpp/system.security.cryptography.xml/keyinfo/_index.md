---
title: "System::Security::Cryptography::Xml::KeyInfo clase"
linktitle: "KeyInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::Xml::KeyInfo clase. Representa el elemento KeyInfo de una firma digital XML o de un cifrado XML. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.security.cryptography.xml/keyinfo/
---
## KeyInfo class


Representa el elemento [KeyInfo](./) de una firma digital XML o de un cifrado XML. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class KeyInfo : public System::Collections::Generic::IEnumerable<SharedPtr<Xml::KeyInfoClause>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddClause](./addclause/)(SharedPtr\<KeyInfoClause\>) |  |
| [get_Count](./get_count/)() |  |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador. |
| [KeyInfo](./keyinfo/)() |  |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Ver también

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Security::Cryptography::Xml](../)
* Library [Aspose.PDF for C++](../../)
