---
title: "Clase System::Security::Cryptography::AsymmetricSignatureFormatter"
linktitle: "AsymmetricSignatureFormatter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::AsymmetricSignatureFormatter. Clase base para formateadores de firmas asimétricas. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.security.cryptography/asymmetricsignatureformatter/
---
## AsymmetricSignatureFormatter class


Clase base para formateadores de firmas asimétricas. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class AsymmetricSignatureFormatter : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [CreateSignature](./createsignature/)(System::ArrayPtr\<uint8_t\>) | Información RTTI. |
| virtual [CreateSignature](./createsignature/)(System::SharedPtr\<HashAlgorithm\>) | Crea la firma para el valor hash especificado. |
| virtual [SetHashAlgorithm](./sethashalgorithm/)(System::String) | Establece el algoritmo hash a usar. |
| virtual [SetKey](./setkey/)(System::SharedPtr\<AsymmetricAlgorithm\>) | Establece el algoritmo asimétrico a usar al calcular la firma. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
