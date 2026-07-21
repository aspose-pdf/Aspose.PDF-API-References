---
title: "Clase System::Security::Cryptography::X509Certificates::X509Extension"
linktitle: "X509Extension"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::X509Certificates::X509Extension. Objeto de extensión para mantener información adicional asociada con el certificado X.509. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.security.cryptography.x509certificates/x509extension/
---
## X509Extension class


Objeto de extensión para mantener información adicional asociada con el certificado X.509. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class X509Extension : public System::Security::Cryptography::AsnEncodedData
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CopyFrom](./copyfrom/)(const SharedPtr\<AsnEncodedData\>\&) override | Copia los datos de extensión de otro objeto. |
| [get_Critical](./get_critical/)() const | Comprueba si la extensión es crítica. |
| [set_Critical](./set_critical/)(bool) | Define si la extensión es crítica. |
| [X509Extension](./x509extension/)(const SharedPtr\<AsnEncodedData\>\&, bool) | Información RTTI. |
| [X509Extension](./x509extension/)(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) | Constructor. |
| [X509Extension](./x509extension/)(const String\&, const ByteArrayPtr\&, bool) | Constructor. |
## Ver también

* Class [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
