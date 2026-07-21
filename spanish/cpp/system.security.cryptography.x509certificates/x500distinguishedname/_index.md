---
title: "Clase System::Security::Cryptography::X509Certificates::X500DistinguishedName"
linktitle: "X500DistinguishedName"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::X509Certificates::X500DistinguishedName. Representa el nombre distinguido de un certificado X509. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.security.cryptography.x509certificates/x500distinguishedname/
---
## X500DistinguishedName class


Representa el nombre distinguido de un certificado X509. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class X500DistinguishedName : public System::Security::Cryptography::AsnEncodedData
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Decode](./decode/)(X500DistinguishedNameFlags) const | Decodifica el nombre usando los parámetros especificados por las banderas. |
| [Format](./format/)(bool) const override | Formatea el nombre para imprimir. |
| [get_Name](./get_name/)() const | Obtiene el nombre distinguido del certificado. |
| [X500DistinguishedName](./x500distinguishedname/)(const SharedPtr\<AsnEncodedData\>\&) | Información RTTI. |
| [X500DistinguishedName](./x500distinguishedname/)(const ByteArrayPtr\&) | Constructor. |
| [X500DistinguishedName](./x500distinguishedname/)(const String\&) | Constructor. |
| [X500DistinguishedName](./x500distinguishedname/)(const SharedPtr\<X500DistinguishedName\>\&) | Constructor de copia. |
| [X500DistinguishedName](./x500distinguishedname/)(const String\&, X500DistinguishedNameFlags) | Constructor. |
## Ver también

* Class [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
