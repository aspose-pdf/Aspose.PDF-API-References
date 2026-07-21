---
title: "System::Security::Cryptography::DSACryptoServiceProvider clase"
linktitle: "DSACryptoServiceProvider"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider clase. Algoritmo DSA en forma CSP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider class


[DSA](../dsa/) algorithm in CSP form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CreateSignature](./createsignature/)(ByteArrayPtr) override | Crear firma [DSA](../dsa/) para los datos especificados. |
| [Dispose](./dispose/)() override | Libera los datos asociados al objeto. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | Constructor. Usa parámetros predeterminados. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const DSAParameters\&) | Constructor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const SharedPtr\<CspParameters\>\&) | Constructor. No implementado. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t) | Constructor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t, const SharedPtr\<CspParameters\>\&) | Constructor. No implementado. |
| [ExportCspBlob](./exportcspblob/)(bool) override | Exporta blob con información de la clave. No implementado. |
| [ExportParameters](./exportparameters/)(bool) override | Exporta parámetros CSP. |
| [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Obtiene un objeto [CspKeyContainerInfo](../cspkeycontainerinfo/). |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Comprueba el algoritmo de intercambio de claves asociado al objeto. |
| [get_KeySize](./get_keysize/)() override | Obtiene el tamaño de la clave. |
| [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Comprueba si la clave se persiste en el objeto CSP. |
| [get_PublicOnly](./get_publiconly/)() const | Comprueba si solo la clave pública está presente en el objeto CSP. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Obtiene el algoritmo de firma a usar. |
| static [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Comprueba si la clave se almacena en el almacén de la máquina en lugar del almacén del usuario. |
| [ImportCspBlob](./importcspblob/)(ByteArrayPtr) override | Importa un blob con información sobre la clave. No implementado. |
| [ImportParameters](./importparameters/)(DSAParameters) override | Importa todos los parámetros de la estructura de datos. |
| [set_PersistKeyInCsp](./set_persistkeyincsp/)(bool) | Define si la clave se persiste en el objeto CSP. |
| static [set_UseMachineKeyStore](./set_usemachinekeystore/)(bool) | Define si la clave se almacena en el almacén de la máquina en lugar del almacén del usuario. |
| [SignData](./signdata/)(const ByteArrayPtr\&) | Calcula la firma del valor de entrada especificado. |
| [SignData](./signdata/)(const SharedPtr\<IO::Stream\>\&) | Calcula la firma del valor de entrada especificado. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t) | Calcula la firma del valor de entrada especificado. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Información RTTI. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Información RTTI. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Información RTTI. |
| [SignHash](./signhash/)(const ByteArrayPtr\&, const String\&) | Calcula la firma del valor de entrada especificado. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&) | Comprueba la firma de los datos. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma de los datos especificados sea válida. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifica que la firma del flujo binario especificado sea válida. |
| [VerifyHash](./verifyhash/)(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) | Comprueba la firma de los datos. |
| [VerifySignature](./verifysignature/)(ByteArrayPtr, ByteArrayPtr) override | Verifica la firma [DSA](../dsa/) para los datos especificados. |
## Ver también

* Class [DSA](../dsa/)
* Class [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
