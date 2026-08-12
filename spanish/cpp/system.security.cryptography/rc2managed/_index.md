---
title: "System::Security::Cryptography::RC2Managed clase"
linktitle: "RC2Managed"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RC2Managed clase. Algoritmo RC2 administrado. Solo se admiten los modos de cifrado ECB, CFB y CBC. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2800
url: /es/cpp/system.security.cryptography/rc2managed/
---
## RC2Managed class


Algoritmo [RC2](../rc2/) administrado. Solo se admiten los modos de cifrado ECB, CFB y CBC. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
class RC2Managed : public System::Security::Cryptography::RC2
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Crea un objeto descifrador con parámetros explícitos. |
| virtual [CreateDecryptor](./createdecryptor/)() | Crea un objeto descifrador con parámetros definidos por el objeto algoritmo. |
| [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Crea un objeto cifrador con parámetros explícitos. |
| virtual [CreateEncryptor](./createencryptor/)() | Crea un objeto cifrador con parámetros definidos por el objeto algoritmo. |
| [GenerateIV](./generateiv/)() override | Crea un valor inicial aleatorio y lo almacena en los internos del algoritmo. |
| [GenerateKey](./generatekey/)() override | Crea una clave aleatoria y la almacena en los internos del algoritmo. |
## Ver también

* Class [RC2](../rc2/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
