---
title: "System::Security::Cryptography::AsymmetricSignatureDeformatter class"
linktitle: "AsymmetricSignatureDeformatter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::AsymmetricSignatureDeformatter class. Clase base para desformateadores de firmas asimétricas. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.security.cryptography/asymmetricsignaturedeformatter/
---
## AsymmetricSignatureDeformatter class


Clase base para desformateadores de firmas asimétricas. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class AsymmetricSignatureDeformatter : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [SetHashAlgorithm](./sethashalgorithm/)(System::String) | Información RTTI. |
| virtual [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) | Establece la clave a usar con el algoritmo. |
| virtual [VerifySignature](./verifysignature/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) | Verifica la firma en los datos. |
| virtual [VerifySignature](./verifysignature/)(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) | Verifica la firma en los datos. No implementado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
