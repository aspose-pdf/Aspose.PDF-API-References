---
title: "Clase System::Security::Cryptography::ECDsaBotan"
linktitle: "ECDsaBotan"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Security::Cryptography::ECDsaBotan. Algoritmo ECDsa en forma Botan. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1400
url: /es/cpp/system.security.cryptography/ecdsabotan/
---
## ECDsaBotan class


[ECDsa](../ecdsa/) algorithm in Botan form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ECDsaBotan : public System::Security::Cryptography::ECDsa
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ECDsaBotan](./ecdsabotan/)() | Constructor. Usa parámetros predeterminados. |
| [ECDsaBotan](./ecdsabotan/)(const ECParameters\&) | Constructor. |
| [ECDsaBotan](./ecdsabotan/)(const ECCurve\&) | Constructor. |
| [ECDsaBotan](./ecdsabotan/)(int32_t) | Constructor. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PublicKey\&) | Constructor. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PrivateKey\&) | Constructor. |
| [ExportExplicitParameters](./exportexplicitparameters/)(bool) override | Exporta parámetros explícitos. |
| [ExportParameters](./exportparameters/)(bool) override | Exporta parámetros nombrados o explícitos. |
| [FromXmlString](./fromxmlstring/)(String) override | Inicializa el objeto usando parámetros codificados en XML. No implementado. |
| [FromXmlString](./fromxmlstring/)(const String\&, ECKeyXmlFormat) | Inicializa el objeto usando parámetros codificados en XML. No implementado. |
| [GenerateKey](./generatekey/)(const ECCurve\&) override | Genera un nuevo par de claves pública/privada para la curva especificada. |
| [get_HashAlgorithm](./get_hashalgorithm/)() const | Obtiene el algoritmo de hash. |
| [HashData](./hashdata/)(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) override | Calcula el valor hash del arreglo de datos especificado usando el algoritmo de hash especificado. |
| [HashData](./hashdata/)(StreamPtr, HashAlgorithmName) override | Calcula el valor hash del flujo binario especificado usando el algoritmo de hash especificado. |
| [ImportParameters](./importparameters/)(const ECParameters\&) override | Importa todos los parámetros de la estructura de datos. |
| [set_HashAlgorithm](./set_hashalgorithm/)(const HashAlgorithmName\&) | Establece el algoritmo de hash. |
| [set_KeySize](./set_keysize/)(int32_t) override | Establece el tamaño de la clave. |
| [SignData](./signdata/)(const ByteArrayPtr\&) | Calcula el valor hash del arreglo de datos especificado y firma el resultado. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t) | Calcula el valor hash del arreglo de datos especificado y firma el resultado. |
| [SignData](./signdata/)(const StreamPtr\&) | Calcula el valor hash del flujo binario especificado y firma el resultado. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Información RTTI. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Información RTTI. |
| virtual [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Información RTTI. |
| [SignHash](./signhash/)(const ByteArrayPtr\&) override | Calcula la firma del valor de entrada especificado. |
| [ToXmlString](./toxmlstring/)(bool) override | Exporta todos los parámetros en formato XML. No implementado. |
| [ToXmlString](./toxmlstring/)(ECKeyXmlFormat) | Exporta todos los parámetros en formato XML. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&) | Verifica que la firma del flujo binario especificado sea válida. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma del flujo binario especificado sea válida. |
| [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr) override | Comprueba la firma de los datos. |
## Ver también

* Class [ECDsa](../ecdsa/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
