---
title: "System::Security::Cryptography::Oid clase"
linktitle: "Oid"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::Oid clase. Identificador de objeto criptográfico. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2500
url: /es/cpp/system.security.cryptography/oid/
---
## Oid class


Identificador de objeto criptográfico. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class Oid : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [FromFriendlyName](./fromfriendlyname/)(const String\&, OidGroup) | Crea un objeto OID a partir del nombre descriptivo OID especificado. |
| static [FromOidValue](./fromoidvalue/)(const String\&, OidGroup) | Crea un objeto OID a partir del valor OID especificado. |
| [get_FriendlyName](./get_friendlyname/)() const | Obtiene el nombre descriptivo del objeto. |
| [get_Value](./get_value/)() const | Obtiene la cadena del identificador del objeto. |
| [Oid](./oid/)() | Información RTTI. |
| [Oid](./oid/)(const SharedPtr\<Oid\>\&) | Constructor de copia. |
| [Oid](./oid/)(const String\&) | Constructor. |
| [Oid](./oid/)(const String\&, const String\&) | Constructor. |
| [set_FriendlyName](./set_friendlyname/)(const String\&) | Establece el nombre descriptivo del objeto. |
| [set_Value](./set_value/)(const String\&) | Establece la cadena del identificador del objeto. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
