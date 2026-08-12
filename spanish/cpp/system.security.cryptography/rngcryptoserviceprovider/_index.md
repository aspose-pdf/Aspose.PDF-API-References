---
title: "Clase System::Security::Cryptography::RNGCryptoServiceProvider"
linktitle: "RNGCryptoServiceProvider"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::RNGCryptoServiceProvider. Generador de números aleatorios que sigue la noción CSP. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 3300
url: /es/cpp/system.security.cryptography/rngcryptoserviceprovider/
---
## RNGCryptoServiceProvider class


Generador de números aleatorios que sigue la noción CSP. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class RNGCryptoServiceProvider : public System::Security::Cryptography::RandomNumberGenerator
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>) override | Llena los elementos existentes del arreglo con bytes aleatorios. |
| [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>) override | Llena los elementos de la vista existente del arreglo con bytes aleatorios. |
| [GetNonZeroBytes](./getnonzerobytes/)(ArrayPtr\<uint8_t\>) override | Rellena los elementos de la matriz existente con bytes aleatorios diferentes de cero. |
| [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<uint8_t\>) override | Rellena los elementos de la vista de matriz existente con bytes aleatorios diferentes de cero. |
| [RNGCryptoServiceProvider](./rngcryptoserviceprovider/)() | Constructor. |
| virtual [~RNGCryptoServiceProvider](./~rngcryptoserviceprovider/)() | Destructor. |
## Ver también

* Class [RandomNumberGenerator](../randomnumbergenerator/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
