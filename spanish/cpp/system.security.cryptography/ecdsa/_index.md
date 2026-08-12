---
title: "Clase System::Security::Cryptography::ECDsa"
linktitle: "ECDsa"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::ECDsa. Clase base para implementaciones del algoritmo ECDsa. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1300
url: /es/cpp/system.security.cryptography/ecdsa/
---
## ECDsa class


Clase base para implementaciones del algoritmo [ECDsa](./). Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class ECDsa : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Create](./create/)() | Crea la implementación predeterminada del algoritmo ECDSA. |
| static [Create](./create/)(const ECCurve\&) | Crea la implementación predeterminada del algoritmo ECDSA con una clave recién creada sobre la curva especificada. |
| static [Create](./create/)(const ECParameters\&) | Crea la implementación predeterminada del algoritmo ECDSA usando los parámetros especificados. |
| static [Create](./create/)(const String\&) | Crea la implementación especificada del algoritmo ECDSA. |
| virtual [ExportExplicitParameters](./exportexplicitparameters/)(bool) | Exporta parámetros explícitos. |
| virtual [ExportParameters](./exportparameters/)(bool) | Exporta parámetros nombrados o explícitos. |
| virtual [GenerateKey](./generatekey/)(const ECCurve\&) | Genera un nuevo par de claves pública/privada para la curva especificada. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Información RTTI. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Obtiene el algoritmo de firma a usar. |
| virtual [ImportParameters](./importparameters/)(const ECParameters\&) | Importa todos los parámetros de la estructura de datos. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado, y firma el resultado. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado, y firma el resultado. |
| virtual [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Calcula el valor hash del flujo binario especificado usando el algoritmo hash especificado, y firma el resultado. |
| virtual [SignHash](./signhash/)(const ByteArrayPtr\&) | Calcula la firma del valor de entrada especificado. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma del flujo binario especificado sea válida. |
| virtual [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr) | Comprueba la firma de los datos. |
## Ver también

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
