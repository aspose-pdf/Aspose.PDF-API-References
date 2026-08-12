---
title: "System::Security::Cryptography::HMACSHA512 class"
linktitle: "HMACSHA512"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::HMACSHA512. Código de autenticación de mensaje basado en hash que utiliza la función hash SHA512. Implementado parcialmente. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1900
url: /es/cpp/system.security.cryptography/hmacsha512/
---
## HMACSHA512 class


Código de autenticación de mensaje basado en hash [Authentication](../../system.security.authentication/) que utiliza la función hash [SHA512](../sha512/). Implementado parcialmente. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class HMACSHA512 : public System::Security::Cryptography::HashAlgorithm
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&) | Calcula [HMAC](../hmac/). |
| [HMACSHA512](./hmacsha512/)() | Constructor. |
| [HMACSHA512](./hmacsha512/)(const System::ArrayPtr\<uint8_t\>\&) | Constructor. |
## Ver también

* Class [HashAlgorithm](../hashalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
