---
title: "System::Security::Cryptography::RSA clase"
linktitle: "RSA"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::RSA clase. Clase base para implementaciones del algoritmo RSA. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3400
url: /es/cpp/system.security.cryptography/rsa/
---
## RSA class


Clase base para implementaciones del algoritmo [RSA](./). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class RSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Create](./create/)() | Crea la implementación predeterminada del algoritmo [RSA](./). |
| static [Create](./create/)(const String\&) | Crea la implementación predeterminada del algoritmo [RSA](./). |
| static [Create](./create/)(int32_t) | Crea la implementación predeterminada del algoritmo [RSA](./) con el tamaño de clave especificado. |
| static [Create](./create/)(const RSAParameters\&) | Crea la implementación predeterminada del algoritmo [RSA](./) con los parámetros especificados. |
| static [CreateFromXmlString](./createfromxmlstring/)(const String\&) | Crea la implementación predeterminada del algoritmo [RSA](./) con los parámetros codificados en XML especificados. |
| virtual [Decrypt](./decrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) | Descifra los datos de entrada usando el modo de relleno especificado. |
| virtual [DecryptValue](./decryptvalue/)(ByteArrayPtr) | Descifra el valor usando la clave privada. |
| virtual [Encrypt](./encrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) | Cifra los datos de entrada usando el modo de relleno especificado. |
| virtual [EncryptValue](./encryptvalue/)(ByteArrayPtr) | Cifra el valor usando la clave privada. |
| virtual [ExportParameters](./exportparameters/)(bool) | Exporta todos los parámetros. |
| [FromXmlString](./fromxmlstring/)(String) override | Inicializa el objeto usando parámetros codificados en XML. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Información RTTI. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Obtiene el algoritmo de firma asociado al objeto CSP. |
| virtual [ImportParameters](./importparameters/)(RSAParameters) | Importa todos los parámetros de la estructura de datos. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash y el relleno especificados, y firma el resultado. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash y el relleno especificados, y firma el resultado. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Calcula el valor hash del flujo binario especificado usando el algoritmo hash y el relleno especificados, y firma el resultado. |
| virtual [SignHash](./signhash/)(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) | Calcula la firma para el valor hash especificado. |
| [ToXmlString](./toxmlstring/)(bool) override | Exporta todos los parámetros en formato XML. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Verifica que la firma del flujo binario especificado sea válida. |
| virtual [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) | Verifica que la firma del hash especificado sea válida. |
## Ver también

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
