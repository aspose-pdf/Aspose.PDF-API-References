---
title: "Clase System::Security::Cryptography::DSA"
linktitle: "DSA"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::DSA. Clase base para implementaciones del algoritmo DSA. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.security.cryptography/dsa/
---
## DSA class


Clase base para implementaciones del algoritmo [DSA](./). Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class DSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Create](./create/)() | Crea la implementación predeterminada del algoritmo [DSA](./). |
| static [Create](./create/)(const String\&) | Crea la implementación predeterminada del algoritmo [DSA](./). |
| static [Create](./create/)(int32_t) | Crea la implementación predeterminada del algoritmo [DSA](./) con el tamaño de clave especificado. |
| static [Create](./create/)(const DSAParameters\&) | Crea la implementación predeterminada del algoritmo [DSA](./) con los parámetros especificados. |
| static [CreateFromXmlString](./createfromxmlstring/)(const String\&) | Crea la implementación predeterminada del algoritmo [DSA](./) con los parámetros codificados en XML especificados. |
| virtual [CreateSignature](./createsignature/)(ByteArrayPtr) | Información RTTI. |
| virtual [ExportParameters](./exportparameters/)(bool) | Exporta todos los parámetros. |
| [FromXmlString](./fromxmlstring/)(String) override | Inicializa el objeto usando parámetros codificados en XML. |
| virtual [ImportParameters](./importparameters/)(DSAParameters) | Importa todos los parámetros de la estructura de datos. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado, y firma el resultado. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado, y firma el resultado. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Calcula el valor hash del flujo binario especificado usando el algoritmo hash especificado, y firma el resultado. |
| [ToXmlString](./toxmlstring/)(bool) override | Exporta todos los parámetros en formato XML. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma del flujo binario especificado sea válida. |
| virtual [VerifySignature](./verifysignature/)(ByteArrayPtr, ByteArrayPtr) | Verifique la firma [DSA](./) para los datos especificados. |
## Ver también

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
