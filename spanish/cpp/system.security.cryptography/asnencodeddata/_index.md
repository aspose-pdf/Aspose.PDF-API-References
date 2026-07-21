---
title: "System::Security::Cryptography::AsnEncodedData clase"
linktitle: "AsnEncodedData"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::AsnEncodedData clase. Datos codificados en ASN.1. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.security.cryptography/asnencodeddata/
---
## AsnEncodedData class


Datos codificados en ASN.1. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class AsnEncodedData : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AsnEncodedData](./asnencodeddata/)(const SharedPtr\<AsnEncodedData\>\&) | Información RTTI. |
| [AsnEncodedData](./asnencodeddata/)(const ByteArrayPtr\&) | Constructor. |
| [AsnEncodedData](./asnencodeddata/)(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) | Constructor. |
| [AsnEncodedData](./asnencodeddata/)(const String\&, const ByteArrayPtr\&) | Constructor. |
| virtual [CopyFrom](./copyfrom/)(const SharedPtr\<AsnEncodedData\>\&) | Copia datos de otro objeto. |
| virtual [Format](./format/)(bool) const | Formatea los datos en una forma legible para humanos. |
| [get_Oid](./get_oid/)() const | Obtiene el identificador de objeto de los datos codificados. |
| [get_RawData](./get_rawdata/)() const | Obtiene los datos codificados en bruto. |
| [set_Oid](./set_oid/)(const SharedPtr\<Oid\>\&) | Establece el identificador de objeto de los datos codificados. |
| [set_RawData](./set_rawdata/)(const ByteArrayPtr\&) | Establece los datos codificados en bruto. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
