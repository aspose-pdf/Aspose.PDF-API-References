---
title: "System::Security::Cryptography::X509Certificates::X509KeyUsageExtension clase"
linktitle: "X509KeyUsageExtension"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::X509Certificates::X509KeyUsageExtension. Objeto de extensión para mantener información adicional sobre el uso de una clave. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1600
url: /es/cpp/system.security.cryptography.x509certificates/x509keyusageextension/
---
## X509KeyUsageExtension class


Objeto de extensión para mantener información adicional sobre el uso de una clave. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class X509KeyUsageExtension : public System::Security::Cryptography::X509Certificates::X509Extension
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CopyFrom](./copyfrom/)(const SharedPtr\<AsnEncodedData\>\&) override | Copia los datos de extensión de otro objeto. |
| [get_KeyUsages](./get_keyusages/)() | Obtiene los usos de la clave. |
| [X509KeyUsageExtension](./x509keyusageextension/)() | Información RTTI. |
| [X509KeyUsageExtension](./x509keyusageextension/)(const SharedPtr\<AsnEncodedData\>\&, bool) | Constructor. |
| [X509KeyUsageExtension](./x509keyusageextension/)(X509KeyUsageFlags, bool) | Constructor. |
## Ver también

* Class [X509Extension](../x509extension/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
