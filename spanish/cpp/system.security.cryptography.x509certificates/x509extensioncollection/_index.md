---
title: "Clase System::Security::Cryptography::X509Certificates::X509ExtensionCollection"
linktitle: "X509ExtensionCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::X509Certificates::X509ExtensionCollection. Colección de objetos de extensión. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1300
url: /es/cpp/system.security.cryptography.x509certificates/x509extensioncollection/
---
## X509ExtensionCollection class


Colección de objetos de extensión. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class X509ExtensionCollection : public System::Collections::Generic::List<SharedPtr<X509Extension>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [idx_get](./idx_get/)(const String\&) const | Accesor. No implementado. |
| [idx_get](./idx_get/)(int) const override | Datos RTTI. |
| [X509ExtensionCollection](./x509extensioncollection/)() | Construye una colección vacía. |
## Ver también

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
