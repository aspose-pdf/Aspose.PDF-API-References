---
title: "Clase System::Security::Cryptography::RijndaelManaged"
linktitle: "RijndaelManaged"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::RijndaelManaged. Algoritmo Rijndael administrado. Solo admite los modos ECB y CFB con relleno None y el modo CBC con rellenos None y Zeros. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3100
url: /es/cpp/system.security.cryptography/rijndaelmanaged/
---
## RijndaelManaged class


Algoritmo administrado [Rijndael](../rijndael/) . Solo admite los modos ECB y CFB con relleno None y el modo CBC con rellenos None y Zeros. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en el puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class RijndaelManaged : public System::Security::Cryptography::Rijndael
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

* Class [Rijndael](../rijndael/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
